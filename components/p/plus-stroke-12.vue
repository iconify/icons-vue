<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erhjj-75b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="erhjj-75b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-stroke-12" /></template>
