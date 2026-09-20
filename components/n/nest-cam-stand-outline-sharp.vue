<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc7234ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-stand-outline-sharp" /></template>
<style>
.hc7234ber {
  fill: currentColor;
  d: path("M10 7.425q-1.384.54-2.32 1.766T6.6 12L6 19h12l-.6-7q-.12-1.588-1.055-2.814Q15.41 7.958 14 7.419V10q0 .846-.577 1.423T12 12t-1.423-.577T10 10zm2.713 3.288Q13 10.425 13 10V6q0-.425-.288-.712T12 5t-.712.288T11 6v4q0 .425.288.713T12 11t.713-.288M12 4q.823 0 1.391.545t.603 1.363v.423q1.812.569 3.034 2.062t1.391 3.484L19.117 20H4.902l.698-8.123q.175-1.99 1.385-3.48q1.21-1.491 3.02-2.06v-.423q.036-.818.604-1.366T12 4");
}

</style>
