<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euesvrbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euesvrbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:play" /></template>
