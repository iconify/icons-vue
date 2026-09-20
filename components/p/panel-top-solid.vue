<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhzu1ybgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhzu1ybgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-top-solid" /></template>
