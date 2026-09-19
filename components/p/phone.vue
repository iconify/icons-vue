<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc0f7gbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc0f7gbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:phone" /></template>
