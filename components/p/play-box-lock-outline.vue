<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh7v1eb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh7v1eb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-box-lock-outline" /></template>
