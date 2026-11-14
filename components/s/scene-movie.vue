<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utivutb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scene-movie" /></template>
<style>
.utivutb7g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.5q0-4.039 2.856-6.894T11.5 1.75t6.894 2.856Q21.25 7.461 21.25 11.5t-2.856 6.894q-.786.786-1.661 1.356H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H11.498q-4.037-.001-6.892-2.856T1.75 11.5M9 7q0 2.5 2.5 2.5T14 7t-2.5-2.5T9 7m-4 6.75q0 2.5 2.5 2.5q1.036 0 1.768-.732T10 13.75t-.732-1.768T7.5 11.25q-2.5 0-2.5 2.5m10.5-2.5q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5");
}

</style>
