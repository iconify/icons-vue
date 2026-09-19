<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_jz1gb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2016,"height":2048};
const content = `<path class="v_jz1gb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sheep" /></template>
