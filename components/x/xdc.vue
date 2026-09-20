<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds7t43jyo.css';
import '../../css/e/e3ss8accz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds7t43jyo"/><path class="e3ss8accz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xdc" /></template>
