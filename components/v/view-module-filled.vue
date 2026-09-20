<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql6nsobnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql6nsobnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-module-filled" /></template>
