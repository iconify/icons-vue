<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alnugs8yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="alnugs8yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:new-hampshire-with-capital-star" /></template>
