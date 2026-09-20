<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvaz16bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yvaz16bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:triangle-with-rounded-corners" /></template>
