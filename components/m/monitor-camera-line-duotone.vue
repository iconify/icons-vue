<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uz-6ybbfc"/><path class="yvkryzb6g"/><path class="evvnrpb1m"/><path class="ta0zdfd_y"/><path class="wqwkkfban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-camera-line-duotone" /></template>
<style>
.evvnrpb1m {
  d: path("M16 22H12M12 22H8M12 22V17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ta0zdfd_y {
  d: path("M22 13H2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uz-6ybbfc {
  d: path("M15 8H16C17.4142 8 18.1213 8 18.5607 7.56066C19 7.12132 19 6.41421 19 5C19 3.58579 19 2.87868 18.5607 2.43934C18.1213 2 17.4142 2 16 2H15C13.5858 2 12.8787 2 12.4393 2.43934C12 2.87868 12 3.58579 12 5C12 6.41421 12 7.12132 12.4393 7.56066C12.8787 8 13.5858 8 15 8Z");
}

.wqwkkfban {
  d: path("M22 10V11C22 13.8284 22 15.2426 21.1213 16.1213C20.2426 17 18.8284 17 16 17H8C5.17157 17 3.75736 17 2.87868 16.1213C2 15.2426 2 13.8284 2 11V9.5C2 6.21252 2 4.56878 2.90796 3.46243C3.07418 3.25989 3.25989 3.07418 3.46243 2.90796C4.56878 2 6.21252 2 9.5 2");
}

.yvkryzb6g {
  d: path("M19 3.75L20.6154 3.07692C21.2416 2.816 21.5547 2.68554 21.7774 2.83397C22 2.98241 22 3.32161 22 4V6C22 6.67839 22 7.01759 21.7774 7.16603C21.5547 7.31446 21.2416 7.184 20.6154 6.92308L19 6.25V3.75Z");
}

</style>
