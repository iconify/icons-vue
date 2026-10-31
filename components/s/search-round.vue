<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcxx56bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcxx56bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:search-round" /></template>
