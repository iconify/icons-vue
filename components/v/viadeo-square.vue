<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioy-9cbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ioy-9cbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:viadeo-square" /></template>
