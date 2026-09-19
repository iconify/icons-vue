<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czxzsbbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="czxzsbbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:weight" /></template>
