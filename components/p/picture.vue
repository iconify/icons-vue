<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dplvd83tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dplvd83tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:picture" /></template>
