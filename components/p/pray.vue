<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve5kkwb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ve5kkwb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pray" /></template>
