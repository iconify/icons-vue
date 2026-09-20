<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee0xevyio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ee0xevyio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:resize-vertical-16" /></template>
