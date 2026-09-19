<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2-bgsbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c2-bgsbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:translation" /></template>
