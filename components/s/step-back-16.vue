<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt7-eyb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zt7-eyb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:step-back-16" /></template>
