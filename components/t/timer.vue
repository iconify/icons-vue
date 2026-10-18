<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wftzxc0om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wftzxc0om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:timer" /></template>
