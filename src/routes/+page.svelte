<script>
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
</script>

<div
  class="w-full h-full bg-gradient-to-b from-indigo-400 to-indigo-500 justify-center flex-col"
>
  <Header />
  <div
    class="w-full h-[35em] bg-gradient-to-b from-blue-700 to-blue-950 flex justify-center"
  >
    <div
      class="w-4/6 h-full px-[50px] py-2.5 opacity-50 bg-indigo-300 border-4 flex-col justify-center items-start gap-2.5 inline-flex"
    />
  </div>
  <div
    class="w-screen h-[1167px] bg-gradient-to-b from-blue-950 via-blue-950 to-indigo-950"
  >
    <div class="w-full h-3/6 flex pt-20">
      <div class="w-1/6 h-full bg-zinc-300 rounded-br-[50px] mx-auto"></div>
      <div class="w-1/6 h-full bg-zinc-300 rounded-br-[50px] mx-auto"></div>
      <div class="w-1/6 h-full bg-zinc-300 rounded-br-[50px] mx-auto"></div>
    </div>
  </div>
  <Footer />
</div>
