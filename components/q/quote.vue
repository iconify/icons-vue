<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byth3i_bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quote" /></template>
<style>
.byth3i_bu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 12v5q0 2.25 2.25 2.25h3.5q2.25 0 2.25-2.25v-4.5q0-2.25-2.25-2.25H6.815q.293-1.559 1.897-2.03q.058-.018.112-.044t.104-.06t.093-.076t.08-.091q.036-.048.064-.101t.047-.111t.028-.117t.01-.12v-2q0-.079-.017-.157q-.031-.146-.116-.269q-.084-.123-.21-.204q-.125-.081-.272-.108q-.146-.027-.292.005Q2.75 5.965 2.75 12m10 5v-5q0-6.035 5.593-7.233q.072-.016.146-.017t.146.012q.073.014.142.041t.13.067q.062.04.115.092q.053.051.095.112t.072.129t.044.14q.017.078.017.157v2q0 .06-.01.12q-.009.06-.028.117t-.047.111t-.064.101q-.037.049-.08.091t-.093.076t-.104.06t-.112.044q-1.604.471-1.897 2.03H18.5q2.25 0 2.25 2.25V17q0 2.25-2.25 2.25H15q-2.25 0-2.25-2.25");
}

</style>
