<script>
	import Block from '$lib/components/Block.svelte';
	import PaperIcon from 'virtual:icons/mingcute/pdf-line';
	import GithubIcon from 'virtual:icons/mdi/github';
	import ArxivIcon from 'virtual:icons/simple-icons/arxiv';
	import Person from '$lib/components/Person.svelte';
	import NavLink from '$lib/components/NavLink.svelte';
	import Call from '../content/call.md';
	import Intro from '../content/intro.md';
	// import PaperList from '$lib/components/PaperList.svelte';
</script>

<svelte:head>
	<title>World Models for Robot Learning Workshop at NeurIPS 2026</title>
</svelte:head>

<div class="text-lg">
	<div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl pt-8 pb-8 text-black md:pt-28">
			<div class="mb-4 text-sm">
				<div class="inline-block rounded-md border border-black px-2 py-1 font-mono">
					NeurIPS WORKSHOP
				</div>
			</div>
			<div class="inline-block text-4xl">World Models for Robot Learning Workshop</div>
			<div class="text-md mt-8 text-gray-800">December 11th or 12th, 2026</div>
			<div class="text-sm text-gray-500">Sydney, Australia</div>
		</div>
	</div>
	<!-- <div class="w-full border-b border-gray-500"></div> -->
	<div
		class="sticky top-0 z-10 my-2 flex w-full items-start justify-center bg-gray-100/70 backdrop-blur-md md:py-1.5"
	>
		<div class="mx-8 w-full max-w-2xl select-none">
			<div
				class="my-2 flex flex-row flex-wrap items-center justify-start font-mono text-sm md:text-base"
			>
				<NavLink href="#schedule">SCHEDULE</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#speakers">SPEAKERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#organizers">ORGANIZERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#call">CALL FOR PAPERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<!-- <NavLink href="#papers">ACCEPTED PAPERS</NavLink> -->
			</div>
		</div>
	</div>
	<!-- <div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl text-black">
			<div class="mt-8 mb-8 flex text-sm md:text-base"></div>
		</div>
	</div> -->
	<Block padding="py-8" class="md:text-justify">
		<Intro />
	</Block>
	<Block>
		<h1 class="mb-6 text-2xl font-bold" id="schedule">Tentative Schedule</h1>
		<div class="mb-6 text-sm">
			<p><strong>Location:</strong> TBD</p>
			<p><strong>Room Capacity:</strong> TBD</p>
		</div>
		<div>
			<table class="w-full border-collapse border border-gray-300 text-sm">
				<thead>
					<tr class="bg-gray-100">
						<th class="border border-gray-300 px-4 py-2 text-left whitespace-nowrap">Time</th>
						<th class="w-full border border-gray-300 px-4 py-2 text-left">Event</th>
					</tr>
				</thead>
				<tbody>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:00 - 9:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Opening Remarks</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:10 - 9:40</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 1</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:40 - 10:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 2</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:10 - 10:50</td>
						<td class="w-full border border-gray-300 px-4 py-2">Oral Presentations</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:50 - 11:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Coffee Break</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:10 - 11:40</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 3</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:40 - 12:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Poster Session 1</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:30 - 13:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Lunch</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">13:30 - 14:00</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 4</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:00 - 14:30</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 5</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:30 - 15:20</td>
						<td class="w-full border border-gray-300 px-4 py-2">Poster Session 2</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:20 - 15:40</td>
						<td class="w-full border border-gray-300 px-4 py-2">Coffee Break</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:40 - 16:10</td>
						<td class="w-full border border-gray-300 px-4 py-2">Invited Talk 6</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:10 - 16:55</td>
						<td class="w-full border border-gray-300 px-4 py-2">Panel Discussion</td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:55 - 17:00</td>
						<td class="w-full border border-gray-300 px-4 py-2">Closing Remarks</td>
					</tr>
				</tbody>
			</table>
		</div>
		<div class="mt-4 text-sm text-gray-600 italic">
			<p>All times are in Australian Eastern Standard Time (AEST).</p>
		</div>
	</Block>
	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="speakers">Invited Speakers</h1>
	</Block>
	<Block>
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Kristen Grauman"
					affiliation="UT Austin"
					link="https://www.cs.utexas.edu/~grauman/"
					image="https://www.cs.utexas.edu/~grauman/kristen.jpg"
				></Person>
				<Person
					name="Jie Tan"
					affiliation="Google DeepMind"
					link="https://www.jie-tan.net/"
					image="https://www.jie-tan.net/img/MyPhoto.jpg"
				></Person>
				<Person
					name="Roberto Calandra"
					affiliation="TU Dresden"
					link="https://lasr.org/people/roberto-calandra"
					image="https://lasr.org/api/images/file/roberto_calandra.png"
				></Person>
				<Person
					name="Tsung-Yi Lin"
					affiliation="NVIDIA Research"
					link="https://tsungyilin.info/"
					image="https://tsungyilin.info/images/tsungyi.jpeg"
				></Person>
				<Person
					name="Hang Zhao"
					affiliation="Tsinghua University / Galaxia AI"
					link="https://hangzhaomit.github.io/"
					image="https://hangzhaomit.github.io/images/profile3.jpg"
				></Person>
				<Person
					name="Wei-Chiu Ma"
					affiliation="Cornell University"
					link="https://www.cs.cornell.edu/~weichiu/"
					image="https://www.cs.cornell.edu/~weichiu/img/weichiu-mit-min.PNG"
				></Person>
				<Person
					name="Franziska Meier"
					affiliation="Meta"
					link="https://fmeier.github.io/"
					image="https://fmeier.github.io/images/me-large.png"
				></Person>
			</div>
		</div>
	</Block>
	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="organizers">Organizers</h1>
	</Block>
	<Block>
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Homanga Bharadhwaj"
					affiliation="Meta Reality Labs"
					link="https://homangab.github.io/"
					image="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=wwW4HRQAAAAJ&citpid=5"
				></Person>
				<Person
					name="Kuang-Huei Lee"
					affiliation="Google DeepMind"
					link="https://kuanghuei.github.io/"
					image="./imgs/kuang.png"
				></Person>
				<Person
					name="Zeyi Liu"
					affiliation="Stanford University"
					link="https://lzylucy.github.io/"
					image="https://lzylucy.github.io/assets/images/profile.jpg"
				></Person>
				<Person
					name="Ruoshi Liu"
					affiliation="Amazon FAR"
					link="https://ruoshiliu.github.io/"
					image="https://ruoshiliu.github.io/resources/ruoshi-1-small.jpg"
				></Person>
				<Person
					name="Wenhao Yu"
					affiliation="Google DeepMind"
					link="https://wenhaoyu.weebly.com/"
					image="https://wenhaoyu.weebly.com/uploads/1/4/2/4/14248981/published/img-1723.jpg?1687933779"
				></Person>
				<Person
					name="Hiroki Furuta"
					affiliation="Google DeepMind / University of Tokyo"
					link="https://frt03.github.io/"
					image="https://frt03.github.io/images/profile_2022.jpeg"
				></Person>
			</div>
		</div>
	</Block>
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="call">Call For Papers</h1>
		<div class="text-base">
			<Call />
		</div>
	</Block>
	<!-- <Block>
		<h1 class="mb-4 text-2xl font-bold" id="papers">Accepted Papers</h1>
		<PaperList />
	</Block> -->

	<div class="mt-8 flex w-full justify-center bg-gray-100 pt-4 font-sans">
		<div class="mx-8 w-full max-w-3xl">
			<div class="flex w-full flex-col items-center justify-start">
				<div class="mt-4 mb-8 text-2xl text-gray-500">
					<a
						href="https://github.com/robowm-ws/robowm-ws.github.io"
						target="_blank"
						rel="noreferrer"
						class="mr-2"
					>
						<GithubIcon class="inline-block hover:text-black" />
					</a>
				</div>
			</div>
			<div class="mb-24 text-sm text-gray-600">
				This website is licensed under a <a
					class="underline"
					href="http://creativecommons.org/licenses/by-sa/4.0/"
					target="_blank"
					rel="noreferrer">Creative Commons Attribution-ShareAlike 4.0 International License</a
				>
				and is based on the
				<a class="underline" href="https://leela-interp.github.io/" target="_blank" rel="noreferrer"
					>Leela Interp</a
				> project. That means you're free to borrow the source code of this website with attribution.
			</div>
		</div>
	</div>
</div>
