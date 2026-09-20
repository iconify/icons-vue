<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqun6cb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tqun6cb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sd" /></template>
