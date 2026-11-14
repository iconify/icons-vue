<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0y61mb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:talent-pipeline" /></template>
<style>
.v0y61mb7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.346 19.353q-.182-.021-.346-.103l-.533-.266q-.109-.054-.208-.123q-.1-.069-.19-.151t-.167-.175t-.141-.197t-.113-.214t-.082-.228q-.033-.116-.049-.237q-.017-.12-.017-.241v-4.301q0-.3-.1-.582q-.099-.283-.287-.516L5.544 6.348q-.077-.096-.14-.202t-.111-.219t-.079-.233t-.046-.242q-.014-.122-.011-.245t.024-.245q.02-.121.057-.239t.09-.228q.053-.112.122-.214q.068-.103.15-.195t.176-.171t.198-.146q.104-.065.217-.116q.112-.05.23-.084q.119-.035.241-.052t.245-.017h10.186q.123 0 .245.017t.241.052q.118.034.23.084t.217.116t.198.146t.176.171t.15.195q.069.102.122.214q.053.111.09.228t.057.239q.021.122.024.245t-.011.245q-.015.123-.046.242t-.079.233q-.047.113-.111.219q-.063.106-.14.202l-4.569 5.671q-.188.233-.287.516q-.1.282-.1.582v2.535m0 .2v1.9m2.75-2.002a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.5 5.75c0-1.75 1.5-2.75 3.25-2.75s3.25 1 3.25 2.75");
}

</style>
