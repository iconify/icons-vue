<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to78y545p"/><path class="v2q6gfb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-gpp-bad" /></template>
<style>
.to78y545p {
  fill: currentColor;
  d: path("M12 2L4 5v6.09c0 5.05 3.41 9.76 8 10.91c4.59-1.15 8-5.86 8-10.91V5zm6 9.09c0 4-2.55 7.7-6 8.83c-3.45-1.13-6-4.82-6-8.83v-4.7l6-2.25l6 2.25zM9.91 8.5L8.5 9.91L10.59 12L8.5 14.09l1.41 1.41L12 13.42l2.09 2.08l1.41-1.41L13.42 12l2.08-2.09l-1.41-1.41L12 10.59z");
}

.v2q6gfb5a {
  fill: currentColor;
  d: path("M6 6.39v4.7c0 4 2.55 7.7 6 8.83c3.45-1.13 6-4.82 6-8.83v-4.7l-6-2.25zm9.5 3.52L13.42 12l2.08 2.09l-1.41 1.41L12 13.42L9.91 15.5L8.5 14.09L10.59 12L8.5 9.91L9.91 8.5L12 10.59l2.09-2.09z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
