<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4ps043ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c4ps043ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-down-alt" /></template>
