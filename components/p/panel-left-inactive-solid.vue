<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj499ub0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj499ub0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-left-inactive-solid" /></template>
