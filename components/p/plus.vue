<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbw5l6n7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mbw5l6n7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:plus" /></template>
