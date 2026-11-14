<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jole1ycxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:remit-tracking" /></template>
<style>
.jole1ycxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.494 11.518q-.066-.066-.119-.143l-.864-1.249q-.127-.184-.303-.323t-.384-.22l-2.449-.958q-.083-.033-.16-.077q-.078-.045-.147-.101q-.07-.055-.13-.121q-.061-.065-.111-.139t-.088-.155q-.039-.08-.065-.166q-.025-.085-.038-.173q-.013-.089-.012-.178t.014-.177t.041-.173q.028-.086.067-.165t.091-.154q.051-.073.112-.137t.132-.12t.149-.098q.077-.044.161-.075l5.928-2.223q.102-.038.208-.061t.214-.031q.108-.007.216.001t.214.031q.106.024.207.063q.102.038.197.091q.094.053.181.118q.086.066.162.144t.14.165q.063.088.114.184q.051.095.087.198q.036.102.057.208q.022.107.027.215t-.004.216t-.035.214t-.066.206l-1.929 4.822M14.25 9.75L20.5 3m-10 10.25h.01m-3.26 2.5h.01M4 18.25h.01M18 21.5c-1.75-1.75-3-3.25-3-4.75a3 3 0 0 1 6 0c0 1.5-1.25 3-3 4.75");
}

</style>
