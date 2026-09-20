<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7dnlchrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7dnlchrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:wrap-text" /></template>
