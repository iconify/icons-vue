<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":165};
const content = `<path class="byp3raceq"/><path class="rxcd4tbtd"/><path class="n26bqxebq"/><path class="pbxb8tb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:microsoft-onedrive" /></template>
<style>
.byp3raceq {
  fill: var(--svg-color--0364b8, #0364b8);
  d: path("m154.66 110.682l52.842-50.534c-10.976-42.8-54.57-68.597-97.37-57.62a80 80 0 0 0-46.952 33.51c.817-.02 91.48 74.644 91.48 74.644");
}

.n26bqxebq {
  fill: var(--svg-color--1490df, #1490df);
  d: path("M207.502 60.148a53 53 0 0 0-3.51-.131a51.8 51.8 0 0 0-20.61 4.254l-.002-.005l-32.022 13.475l35.302 43.607l63.11 15.341c13.62-25.283 4.164-56.82-21.12-70.44a52 52 0 0 0-21.148-6.1");
}

.pbxb8tb7v {
  fill: var(--svg-color--28a8ea, #28a8ea);
  d: path("M11.498 136.596a63.91 63.91 0 0 0 52.5 27.417h139.994a51.99 51.99 0 0 0 45.778-27.323l-98.413-58.95z");
}

.rxcd4tbtd {
  fill: var(--svg-color--0078d4, #0078d4);
  d: path("m97.618 45.552l-.002.009a63.7 63.7 0 0 0-33.619-9.543c-.274 0-.544.017-.818.02C27.852 36.476-.432 65.47.005 100.798a63.97 63.97 0 0 0 11.493 35.798l79.165-9.915l60.694-48.94z");
}

</style>
