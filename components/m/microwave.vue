<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tycoh_b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":832};
const content = `<path class="tycoh_b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:microwave" /></template>
