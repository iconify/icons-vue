<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl5-w3b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl5-w3b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-christianity-outline" /></template>
