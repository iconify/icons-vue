<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5lze41zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5lze41zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:notification-circle-filled" /></template>
