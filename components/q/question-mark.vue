<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb34hpbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb34hpbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:question-mark" /></template>
