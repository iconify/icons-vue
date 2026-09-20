<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py5k_qboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="py5k_qboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pet-grooming" /></template>
