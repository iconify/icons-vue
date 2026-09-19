<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmov_dv6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kmov_dv6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:repeat" /></template>
