<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5pk8r8ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="x5pk8r8ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:whale-watching" /></template>
