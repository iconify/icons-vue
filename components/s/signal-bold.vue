<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2w_eimj"/><path class="fgadp_2sf"/><path class="t6ede50nt"/><path class="mhr5ze81l"/><path class="u7dnju8fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signal-bold" /></template>
<style>
.fgadp_2sf {
  fill: currentColor;
  d: path("M7.5 15.25C7.91421 15.25 8.25 15.5858 8.25 16V20C8.25 20.4142 7.91421 20.75 7.5 20.75C7.08579 20.75 6.75 20.4142 6.75 20V16C6.75 15.5858 7.08579 15.25 7.5 15.25Z");
}

.hl2w_eimj {
  fill: currentColor;
  d: path("M3 19.25C3.41421 19.25 3.75 19.5858 3.75 20C3.75 20.4142 3.41421 20.75 3 20.75C2.58579 20.75 2.25 20.4142 2.25 20C2.25 19.5858 2.58579 19.25 3 19.25Z");
}

.mhr5ze81l {
  fill: currentColor;
  d: path("M16.5 7.25C16.9142 7.25 17.25 7.58579 17.25 8V20C17.25 20.4142 16.9142 20.75 16.5 20.75C16.0858 20.75 15.75 20.4142 15.75 20V8C15.75 7.58579 16.0858 7.25 16.5 7.25Z");
}

.t6ede50nt {
  fill: currentColor;
  d: path("M12 11.25C12.4142 11.25 12.75 11.5858 12.75 12V20C12.75 20.4142 12.4142 20.75 12 20.75C11.5858 20.75 11.25 20.4142 11.25 20V12C11.25 11.5858 11.5858 11.25 12 11.25Z");
}

.u7dnju8fd {
  fill: currentColor;
  d: path("M21 3.25C21.4142 3.25 21.75 3.58579 21.75 4V20C21.75 20.4142 21.4142 20.75 21 20.75C20.5858 20.75 20.25 20.4142 20.25 20V4C20.25 3.58579 20.5858 3.25 21 3.25Z");
}

</style>
