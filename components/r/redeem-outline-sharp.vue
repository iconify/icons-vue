<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6z5gn7um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:redeem-outline-sharp" /></template>
<style>
.f6z5gn7um {
  fill: currentColor;
  d: path("M4 16.577V19h16v-2.423zM3 7.039h4.95q-.125-.225-.21-.475q-.086-.25-.086-.525q0-.847.577-1.424q.577-.576 1.423-.576q.508 0 .939.266t.753.66l.615.843l.616-.843q.315-.407.753-.667t.943-.26q.842 0 1.42.577q.576.577.576 1.424q0 .275-.076.525t-.22.475H21V20H3zm1 7.384h16V8.039h-6.446l1.985 2.734l-.793.573l-2.785-3.792l-2.784 3.792l-.792-.573l1.973-2.734H4zm6.366-7.672q.288-.287.288-.712t-.288-.713t-.712-.287t-.713.287t-.287.713t.287.712t.713.288t.712-.288m3.903.288q.425 0 .713-.288t.287-.712t-.287-.713t-.713-.287t-.712.287t-.288.713t.288.712t.712.288");
}

</style>
