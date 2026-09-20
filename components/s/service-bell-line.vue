<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgqjkcb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgqjkcb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:service-bell-line" /></template>
