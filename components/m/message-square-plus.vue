<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxxrf2bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxxrf2bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-square-plus" /></template>
