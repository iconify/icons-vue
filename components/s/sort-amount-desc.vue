<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf0npmbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="sf0npmbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:sort-amount-desc" /></template>
