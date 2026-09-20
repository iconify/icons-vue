<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrs8ykbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yrs8ykbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:search" /></template>
