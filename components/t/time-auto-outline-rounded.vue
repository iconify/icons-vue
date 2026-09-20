<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0c7ml9ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:time-auto-outline-rounded" /></template>
<style>
.o0c7ml9ag {
  fill: currentColor;
  d: path("M10.329 14.558h3.273l.625 1.823q.062.16.171.235q.11.076.27.076q.263 0 .39-.205q.129-.204.056-.437l-2.408-6.933q-.062-.16-.206-.267t-.329-.108h-.4q-.185 0-.329.108t-.206.267l-2.432 6.944q-.073.233.064.432t.395.2q.16 0 .27-.086t.17-.246zm.302-.874l1.35-3.915l1.325 3.915zM9.885 2.5q-.214 0-.357-.143q-.144-.144-.144-.357t.144-.357t.357-.143h4.23q.214 0 .357.143q.144.144.144.357t-.144.357q-.143.143-.356.143zm-.997 17.874q-1.455-.626-2.546-1.716t-1.716-2.545T4 13t.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l.738-.739q.14-.14.345-.15t.363.15t.16.354t-.16.354l-.738.738q.95 1.135 1.469 2.493T20 13q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626m8.063-2.424Q19 15.9 19 13t-2.05-4.95T12 6T7.05 8.05T5 13t2.05 4.95T12 20t4.95-2.05M12 13");
}

</style>
