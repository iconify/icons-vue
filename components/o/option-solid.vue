<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ery9h55ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ery9h55ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:option-solid" /></template>
