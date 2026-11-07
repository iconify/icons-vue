<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zimgv8bvk.css';
import '../../css/c/cudl-bmyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zimgv8bvk"/><path class="cudl-bmyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plmail-dark" /></template>
