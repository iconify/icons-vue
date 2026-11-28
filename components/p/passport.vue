<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7q6un40l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v7q6un40l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:passport" /></template>
