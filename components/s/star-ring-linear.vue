<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hvfw3sb6l.css';
import '../../css/i/ifaxiac7c.css';
import '../../css/f/fhnye3b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hvfw3sb6l"/><path class="ifaxiac7c"/><path class="fhnye3b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-ring-linear" /></template>
