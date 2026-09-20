<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zypgudbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zypgudbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shuffle" /></template>
