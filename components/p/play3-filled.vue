<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9r14fl0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9r14fl0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:play3-filled" /></template>
