<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu8aw7boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qu8aw7boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pie-chart-alt-outline" /></template>
