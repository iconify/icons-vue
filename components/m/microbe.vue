<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrbmz5bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lrbmz5bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:microbe" /></template>
