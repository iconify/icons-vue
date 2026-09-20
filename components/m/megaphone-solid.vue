<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op9huqmep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="op9huqmep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:megaphone-solid" /></template>
