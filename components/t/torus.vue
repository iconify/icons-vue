<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rid0luifp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rid0luifp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:torus" /></template>
