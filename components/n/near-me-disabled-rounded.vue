<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crfl6-b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:near-me-disabled-rounded" /></template>
<style>
.crfl6-b1t {
  fill: currentColor;
  d: path("m12.694 18.233l-1.99-4.975l-4.995-2.03q-.267-.105-.388-.32q-.121-.214-.121-.431q0-.218.124-.432t.391-.32L9.663 8.24L4.52 3.096q-.146-.146-.156-.347t.156-.366t.357-.166t.357.166l16.384 16.384q.146.146.156.344t-.156.364t-.357.165q-.19 0-.356-.165l-5.202-5.196l-1.504 3.948q-.106.267-.32.391t-.432.124t-.431-.12q-.215-.122-.32-.39M18.83 5.751q.065.23-.04.472l-1.448 3.821q-.162.404-.6.5q-.439.096-.743-.208l-2.373-2.372q-.304-.304-.217-.743q.086-.438.49-.6l3.84-1.448q.243-.106.473-.04q.23.065.391.226q.162.162.227.392");
}

</style>
