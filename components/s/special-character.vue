<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgvxtg2bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgvxtg2bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:special-character" /></template>
