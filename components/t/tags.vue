<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px_2qccme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="px_2qccme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:tags" /></template>
