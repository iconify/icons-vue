<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v74qen_bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v74qen_bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tent-tree" /></template>
