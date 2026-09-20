<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxr668a_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxr668a_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:usercase-filled" /></template>
