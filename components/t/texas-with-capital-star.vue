<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egub1acbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="egub1acbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:texas-with-capital-star" /></template>
