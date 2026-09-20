<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl5-qvbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hl5-qvbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:racquet" /></template>
