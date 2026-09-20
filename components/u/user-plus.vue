<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqaz2vbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqaz2vbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-plus" /></template>
