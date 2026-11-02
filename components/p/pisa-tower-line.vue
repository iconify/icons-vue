<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvd1gsics.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvd1gsics"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pisa-tower-line" /></template>
