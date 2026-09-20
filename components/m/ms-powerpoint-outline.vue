<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt7s2fbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lt7s2fbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ms-powerpoint-outline" /></template>
