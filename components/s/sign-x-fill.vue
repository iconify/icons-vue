<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmu0557rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmu0557rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-x-fill" /></template>
