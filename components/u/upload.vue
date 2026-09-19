<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irr2v7bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="irr2v7bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:upload" /></template>
