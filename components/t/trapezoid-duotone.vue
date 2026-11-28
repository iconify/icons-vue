<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isg9b6-va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isg9b6-va primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trapezoid-duotone" /></template>
