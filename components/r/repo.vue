<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z29616bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="z29616bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo" /></template>
