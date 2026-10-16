<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgre77bfz.css';
import '../../css/p/pk8m0abcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cgre77bfz"/><path class="pk8m0abcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wire-stripper-48" /></template>
