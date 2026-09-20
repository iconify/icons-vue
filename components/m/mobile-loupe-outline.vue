<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbqcfgc_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-loupe-outline" /></template>
<style>
.zbqcfgc_p {
  fill: currentColor;
  d: path("M7 21V3v5.14v-.025zm5.588-14.913q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22M10.252 22H7.616q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144v4.669q-.25-.054-.497-.084l-.503-.06V3.614q0-.269-.173-.442T16.46 3H7.616q-.27 0-.443.173T7 3.616v16.769q0 .269.173.442t.443.173h1.83q.166.287.369.516q.202.228.437.484m6.248.5q-2.514 0-4.282-1.774T10.5 16.419q.05-2.407 1.78-4.138t4.14-1.781q2.532-.05 4.306 1.718T22.5 16.5v4.385q0 .67-.472 1.143q-.472.472-1.143.472zm-.442-3.5v-2.058h-1.933v-.884h1.933V14h.884v2.058h1.933v.884h-1.933V19zm3.985 1.043Q21.5 18.587 21.5 16.5t-1.457-3.543T16.5 11.5t-3.543 1.457T11.5 16.5t1.457 3.543T16.5 21.5t3.543-1.457");
}

</style>
