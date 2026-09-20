<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtma7g7nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtma7g7nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-x-sharp" /></template>
