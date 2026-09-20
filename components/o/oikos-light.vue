<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcgyv0bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lcgyv0bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oikos-light" /></template>
