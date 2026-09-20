<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ro0_byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="k5ro0_byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rss" /></template>
