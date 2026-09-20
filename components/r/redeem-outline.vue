<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-5b0vdxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:redeem-outline" /></template>
<style>
.d-5b0vdxq {
  fill: currentColor;
  d: path("M4 16.577v1.808q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-1.808zm.616-9.538H7.95q-.125-.225-.21-.475q-.086-.25-.086-.525q0-.847.577-1.424q.577-.576 1.423-.576q.5 0 .936.262q.435.263.756.664l.616.843l.615-.843q.315-.407.754-.667q.438-.26.938-.26q.847 0 1.423.577t.577 1.424q0 .275-.076.525t-.22.475h3.411q.691 0 1.153.462T21 8.654v9.73q0 .691-.463 1.154T19.385 20H4.615q-.69 0-1.152-.462T3 18.384v-9.73q0-.69.463-1.153t1.152-.462M4 14.423h16v-5.77q0-.23-.192-.422t-.424-.192h-5.83l1.985 2.734l-.793.573l-2.785-3.792l-2.784 3.792l-.792-.573l1.973-2.734H4.615q-.23 0-.423.192T4 8.654zm6.366-7.672q.288-.288.288-.713t-.288-.712t-.712-.288t-.713.288t-.287.712t.287.713t.713.287t.712-.287m3.903.287q.425 0 .713-.287t.287-.713t-.287-.712t-.713-.288t-.712.288t-.288.712t.288.713t.712.287");
}

</style>
