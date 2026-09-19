<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew-dqmb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ew-dqmb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:meta" /></template>
