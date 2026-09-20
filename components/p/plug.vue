<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0xzv1mye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g0xzv1mye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:plug" /></template>
