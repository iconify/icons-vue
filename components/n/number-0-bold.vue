<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixsi4-b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixsi4-b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-0-bold" /></template>
