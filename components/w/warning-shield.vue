<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tns77oa9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tns77oa9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:warning-shield" /></template>
