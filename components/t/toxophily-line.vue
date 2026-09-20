<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeo0uab8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeo0uab8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toxophily-line" /></template>
