<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6wc6fb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6wc6fb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:scanner-thin" /></template>
