<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e--6l4fbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:soundbar-outline" /></template>
<style>
.e--6l4fbi {
  fill: currentColor;
  d: path("M11.5 12.577h1V9.692h-1zM5.77 18v-1H9v1zM15 18v-1h3.23v1zm-7.73-5.423q.613 0 1.027-.414q.414-.415.414-1.019t-.414-1.018t-1.018-.414t-1.028.417t-.424 1.005q0 .614.423 1.028q.424.415 1.02.415m9.455.02q.6 0 1.034-.428q.433-.428.433-1.028t-.431-1.025t-1.038-.424t-1.03.424t-.424 1.025t.428 1.028t1.028.427M4.615 15.27q-.69 0-1.152-.462T3 13.652V8.617q0-.692.463-1.155T4.615 7h14.77q.69 0 1.152.463T21 8.617v5.035q0 .692-.463 1.155t-1.153.462zm0-1h14.77q.269 0 .442-.173t.173-.442V8.616q0-.27-.173-.443T19.385 8H4.615q-.269 0-.442.173T4 8.616v5.038q0 .269.173.442t.443.173M12 11.135");
}

</style>
