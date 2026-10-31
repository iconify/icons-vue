<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5g9r1bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5g9r1bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-merge-round" /></template>
