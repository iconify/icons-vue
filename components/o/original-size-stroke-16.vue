<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2r3iofuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v2r3iofuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:original-size-stroke-16" /></template>
