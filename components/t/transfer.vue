<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddwf0vbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddwf0vbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:transfer" /></template>
