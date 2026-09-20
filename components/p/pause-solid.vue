<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl407cb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nl407cb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:pause-solid" /></template>
