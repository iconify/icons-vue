<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxfmooi8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qxfmooi8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:toilet-sign-man-flat" /></template>
