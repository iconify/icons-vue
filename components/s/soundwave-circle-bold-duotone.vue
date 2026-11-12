<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path clip-rule="evenodd" class="y97q9l2_w"/><path class="v6bcz-bfu"/><path class="zefgjeb6c"/><path class="tvb3o9byw"/></g><path class="lapw_ob3a"/><path class="zhamvh7br"/><path class="gmc1a7rtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:soundwave-circle-bold-duotone" /></template>
<style>
.gmc1a7rtd {
  fill: currentColor;
  d: path("M17 9.25C17.4142 9.25 17.75 9.58579 17.75 10V14C17.75 14.4142 17.4142 14.75 17 14.75C16.5858 14.75 16.25 14.4142 16.25 14V10C16.25 9.58579 16.5858 9.25 17 9.25Z");
}

.lapw_ob3a {
  fill: currentColor;
  d: path("M12 6.25C12.4142 6.25 12.75 6.58579 12.75 7V17C12.75 17.4142 12.4142 17.75 12 17.75C11.5858 17.75 11.25 17.4142 11.25 17V7C11.25 6.58579 11.5858 6.25 12 6.25Z");
}

.tvb3o9byw {
  d: path("M17 9.25C17.4142 9.25 17.75 9.58579 17.75 10V14C17.75 14.4142 17.4142 14.75 17 14.75C16.5858 14.75 16.25 14.4142 16.25 14V10C16.25 9.58579 16.5858 9.25 17 9.25Z");
}

.v6bcz-bfu {
  d: path("M12 6.25C12.4142 6.25 12.75 6.58579 12.75 7V17C12.75 17.4142 12.4142 17.75 12 17.75C11.5858 17.75 11.25 17.4142 11.25 17V7C11.25 6.58579 11.5858 6.25 12 6.25Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y97q9l2_w {
  fill-rule: evenodd;
  d: path("M12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2ZM12.75 7C12.75 6.58579 12.4142 6.25 12 6.25C11.5858 6.25 11.25 6.58579 11.25 7V17C11.25 17.4142 11.5858 17.75 12 17.75C12.4142 17.75 12.75 17.4142 12.75 17V7ZM7.75 9C7.75 8.58579 7.41421 8.25 7 8.25C6.58579 8.25 6.25 8.58579 6.25 9V15C6.25 15.4142 6.58579 15.75 7 15.75C7.41421 15.75 7.75 15.4142 7.75 15V9ZM17.75 10C17.75 9.58579 17.4142 9.25 17 9.25C16.5858 9.25 16.25 9.58579 16.25 10V14C16.25 14.4142 16.5858 14.75 17 14.75C17.4142 14.75 17.75 14.4142 17.75 14V10Z");
}

.zefgjeb6c {
  d: path("M7 8.25C7.41421 8.25 7.75 8.58579 7.75 9V15C7.75 15.4142 7.41421 15.75 7 15.75C6.58579 15.75 6.25 15.4142 6.25 15V9C6.25 8.58579 6.58579 8.25 7 8.25Z");
}

.zhamvh7br {
  fill: currentColor;
  d: path("M7 8.25C7.41421 8.25 7.75 8.58579 7.75 9V15C7.75 15.4142 7.41421 15.75 7 15.75C6.58579 15.75 6.25 15.4142 6.25 15V9C6.25 8.58579 6.58579 8.25 7 8.25Z");
}

</style>
