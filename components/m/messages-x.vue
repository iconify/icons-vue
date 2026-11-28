<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xclfi9b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xclfi9b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:messages-x" /></template>
