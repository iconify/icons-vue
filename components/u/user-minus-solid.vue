<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub4w97u6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ub4w97u6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:user-minus-solid" /></template>
