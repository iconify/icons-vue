<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-rn6bcfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m-rn6bcfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-apple-and-pound" /></template>
