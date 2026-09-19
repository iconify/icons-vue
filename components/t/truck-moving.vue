<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg609qbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="eg609qbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:truck-moving" /></template>
