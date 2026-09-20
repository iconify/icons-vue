<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp6mlgbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cp6mlgbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pinterest" /></template>
