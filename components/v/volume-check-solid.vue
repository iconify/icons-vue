<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndoybccwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndoybccwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-check-solid" /></template>
