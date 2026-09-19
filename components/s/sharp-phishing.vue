<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ymfub7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-phishing" /></template>
<style>
.k4ymfub7f {
  fill: currentColor;
  d: path("M19 9c0-1.3-.84-2.4-2-2.82V2h-2v4.18C13.84 6.6 13 7.7 13 9s.84 2.4 2 2.82V15c0 2.21-1.79 4-4 4s-4-1.79-4-4v-1h3L5 9v6c0 3.31 2.69 6 6 6s6-2.69 6-6v-3.18c1.16-.42 2-1.52 2-2.82m-3 1c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

</style>
