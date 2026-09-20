<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h40b46bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h40b46bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:move-1" /></template>
