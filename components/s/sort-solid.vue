<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj2o055wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj2o055wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sort-solid" /></template>
