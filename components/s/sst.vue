<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keia154hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keia154hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:sst" /></template>
