<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpyn0l9lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpyn0l9lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:repeat" /></template>
