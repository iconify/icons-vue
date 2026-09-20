<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nse6lu4jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-3-alt-1-outline" /></template>
<style>
.nse6lu4jj {
  fill: currentColor;
  d: path("M9.692 16.635h3.616q.433 0 .716-.308q.284-.308.284-.712v-2q0-.21-.146-.393T13.73 13q.285-.058.43-.241q.147-.184.147-.375v-2.019q0-.404-.293-.702t-.707-.298H9.692v1h3.616V12.5h-2.616v1h2.616v2.135H9.692zM9.385 2.5v-1h5.23v1zm-.497 17.874q-1.455-.626-2.546-1.716t-1.716-2.545T4 13t.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l1.092-1.093l.708.708l-1.092 1.092q.95 1.135 1.469 2.493T20 13q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626m8.063-2.424Q19 15.9 19 13t-2.05-4.95T12 6T7.05 8.05T5 13t2.05 4.95T12 20t4.95-2.05M12 13");
}

</style>
