<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfuy65bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfuy65bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pencil-square" /></template>
