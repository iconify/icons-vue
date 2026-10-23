<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z45_lubjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z45_lubjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-share" /></template>
