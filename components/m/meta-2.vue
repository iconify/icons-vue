<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klya34bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="klya34bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:meta-2" /></template>
