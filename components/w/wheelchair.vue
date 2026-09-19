<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc7t5-bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="lc7t5-bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:wheelchair" /></template>
