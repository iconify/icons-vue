<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlr6ijy8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mlr6ijy8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:webpack-solid" /></template>
