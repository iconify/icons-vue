<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cknplebfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cknplebfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:numbers-90-sort-descending-fill" /></template>
