<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrv606btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrv606btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plane-takeoff-filled" /></template>
