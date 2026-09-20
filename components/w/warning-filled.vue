<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xusyuacyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xusyuacyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-filled" /></template>
