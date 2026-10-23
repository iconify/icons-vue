<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhihflyst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhihflyst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shredder" /></template>
