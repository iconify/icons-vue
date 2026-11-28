<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd4x32brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nd4x32brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:shield-user-fill" /></template>
