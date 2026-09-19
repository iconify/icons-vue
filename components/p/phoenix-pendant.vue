<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob12t-xdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob12t-xdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:phoenix-pendant" /></template>
