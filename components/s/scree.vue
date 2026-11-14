<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwrrgb30n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scree" /></template>
<style>
.nwrrgb30n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.592 6.518l1.646-2.116q1.005-1.293 2.544-.734l3.34 1.215q1.701.618 1.462 2.412l-.186 1.391q-.232 1.745-1.981 1.939l-2.935.326q-.599.067-1.151-.175L8.466 9.96q-1.008-.441-1.279-1.507q-.27-1.067.405-1.935m4.848 12.233q-.112 1 .559 1.749t1.677.75h5q1.986-.001 2.232-1.971l.237-1.896q.149-1.185-.75-1.973l-2.486-2.173q-1.373-1.202-2.832-.107l-2.508 1.881q-.779.584-.886 1.551zm-10.147-.343v-.001l.772-2.83q.318-1.162 1.46-1.543l2.571-.857q1.75-.583 2.665 1.019l1.076 1.883q.471.823.21 1.735l-.515 1.804q-.466 1.632-2.163 1.632H4.464q-1.113 0-1.788-.884q-.676-.885-.383-1.958");
}

</style>
