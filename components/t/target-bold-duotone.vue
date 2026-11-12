<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="rq9nj4b_b"/><path class="p1iyhdoir"/><path class="kb4z_3z1y"/><path class="lwuh2ntst"/><path class="y01l18b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:target-bold-duotone" /></template>
<style>
.kb4z_3z1y {
  fill: currentColor;
  d: path("M5 11.25C5.41421 11.25 5.75 11.5858 5.75 12C5.75 12.4142 5.41421 12.75 5 12.75H2.02734C2.00899 12.5024 2 12.2523 2 12C2 11.7477 2.00899 11.4976 2.02734 11.25H5Z");
}

.lwuh2ntst {
  fill: currentColor;
  d: path("M21.9727 11.25C21.991 11.4976 22 11.7477 22 12C22 12.2523 21.991 12.5024 21.9727 12.75H19C18.5858 12.75 18.25 12.4142 18.25 12C18.25 11.5858 18.5858 11.25 19 11.25H21.9727Z");
}

.mpv5vhdla {
  fill: currentColor;
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.p1iyhdoir {
  fill: currentColor;
  d: path("M12 9.25C12.4142 9.25 12.75 9.58579 12.75 10V11.25H14C14.4142 11.25 14.75 11.5858 14.75 12C14.75 12.4142 14.4142 12.75 14 12.75H12.75V14C12.75 14.4142 12.4142 14.75 12 14.75C11.5858 14.75 11.25 14.4142 11.25 14V12.75H10C9.58579 12.75 9.25 12.4142 9.25 12C9.25 11.5858 9.58579 11.25 10 11.25H11.25V10C11.25 9.58579 11.5858 9.25 12 9.25Z");
}

.rq9nj4b_b {
  fill: currentColor;
  d: path("M12 18.25C12.4142 18.25 12.75 18.5858 12.75 19V21.9727C12.5024 21.991 12.2523 22 12 22C11.7477 22 11.4976 21.991 11.25 21.9727V19C11.25 18.5858 11.5858 18.25 12 18.25Z");
}

.y01l18b7v {
  fill: currentColor;
  d: path("M12 2C12.2523 2 12.5024 2.00899 12.75 2.02734V5C12.75 5.41421 12.4142 5.75 12 5.75C11.5858 5.75 11.25 5.41421 11.25 5V2.02734C11.4976 2.00899 11.7477 2 12 2Z");
}

</style>
