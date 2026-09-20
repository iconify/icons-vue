<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeaf2n6lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeaf2n6lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pregnancy-sperm-1" /></template>
