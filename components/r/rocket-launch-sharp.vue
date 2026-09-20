<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5qhrzbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rocket-launch-sharp" /></template>
<style>
.d5qhrzbpu {
  fill: currentColor;
  d: path("m3.7 11.287l3.623-3.624q.293-.292.671-.413t.783-.04l1.415.294Q9.073 8.873 8.366 9.98t-1.414 2.688zm4.125 1.62q.652-1.51 1.563-2.89q.91-1.378 2.08-2.548q1.873-1.873 4.073-2.806t4.746-.797q.136 2.546-.795 4.746t-2.803 4.073q-1.164 1.163-2.548 2.07t-2.897 1.559zm7.236-2.328q.626 0 1.066-.44q.44-.441.44-1.057t-.44-1.057q-.44-.44-1.066-.44t-1.067.44t-.44 1.057t.44 1.056t1.067.44m-2.228 9.874L11.444 17.2q1.581-.706 2.691-1.423q1.111-.717 2.48-1.836l.289 1.415q.08.404-.031.785q-.111.382-.404.675zm-7.687-4.306q.587-.586 1.423-.58t1.423.594q.587.586.587 1.423t-.587 1.423q-.51.51-1.635.873t-2.605.502q.138-1.479.511-2.602t.883-1.633");
}

</style>
