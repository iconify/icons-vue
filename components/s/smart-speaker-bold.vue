<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6eyaewnx.css';
import '../../css/c/cr0ueab8d.css';
import '../../css/e/esa97-7_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6eyaewnx"/><path class="cr0ueab8d"/><path class="esa97-7_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-speaker-bold" /></template>
