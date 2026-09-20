<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1kgi7btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speech-to-text-2-outline-sharp" /></template>
<style>
.a1kgi7btp {
  fill: currentColor;
  d: path("M19 4v16zM7 21v-3.27h1V20h11V4h-7.5V3H20v18zm.5-11.115q-.639 0-1.07-.431T6 8.384V4q0-.639.43-1.07T7.5 2.5q.614 0 1.057.43T9 4v4.385q0 .638-.443 1.069t-1.057.43M7 15.5v-2.523q-1.833-.171-3.109-1.424Q2.616 10.3 2.616 8.5h1q0 1.52 1.163 2.51T7.5 12t2.721-.99t1.163-2.51h1q0 1.8-1.275 3.053Q9.833 12.806 8 12.977V15.5zm3.5 2.23h6v-1h-6zm0-3h4v-1h-4z");
}

</style>
