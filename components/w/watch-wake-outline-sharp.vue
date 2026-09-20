<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar870pgbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-wake-outline-sharp" /></template>
<style>
.ar870pgbj {
  fill: currentColor;
  d: path("M8.73 4h2.54zm0 16h2.54zm8.886-4v-1h1.615v1zm0-3.5v-1h2.615v1zm0-3.5V7.975h3.615V9zM7.962 21l-1.12-3.934q-1.257-.739-2.05-2.087T4 12t.792-2.979q.793-1.348 2.05-2.087L7.962 3h4.077l1.119 3.935q1.258.738 2.05 2.086T16 12t-.792 2.979t-2.05 2.087L12.038 21zm5.576-5.462Q15 14.075 15 12t-1.463-3.537T10 7T6.463 8.463T5 12t1.463 3.538T10 17t3.538-1.463m-5.476-9.21q.519-.163.991-.248T10 5.994t.947.085t.991.248L11.27 4H8.731zM8.73 20h2.538l.67-2.327q-.52.164-.992.236T10 17.98t-.947-.072t-.991-.236z");
}

</style>
