<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaw2a-pso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eaw2a-pso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wikis" /></template>
