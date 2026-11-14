<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx80j8h8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:security-badge" /></template>
<style>
.hx80j8h8o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.779 4.804l-7.5-3Q12.144 1.75 12 1.75t-.279.054l-7.5 3q-.104.041-.191.112q-.088.07-.151.164q-.063.093-.096.2t-.033.22V11q0 7.654 7.945 11.185q.146.065.305.065t.305-.065Q20.25 18.654 20.25 11V5.5q0-.112-.033-.22q-.033-.107-.096-.2t-.151-.164q-.087-.071-.191-.112m-6.471 2.761l.261.574q.182.4.62.437l.623.052q.917.076 1.208.949t-.397 1.484l-.46.408q-.332.296-.232.73l.184.794q.215.927-.563 1.477t-1.581.037l-.569-.362q-.402-.256-.804 0l-.57.363q-.802.512-1.58-.038t-.563-1.478l.184-.794q.1-.433-.232-.728l-.46-.41q-.688-.61-.397-1.483t1.208-.949l.623-.052q.438-.037.62-.437l.261-.574q.384-.842 1.308-.842t1.307.841z");
}

</style>
