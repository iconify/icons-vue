<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8_owuznp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n8_owuznp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:refresh" /></template>
