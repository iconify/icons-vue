<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpwszlu2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rpwszlu2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:redo-ltr" /></template>
