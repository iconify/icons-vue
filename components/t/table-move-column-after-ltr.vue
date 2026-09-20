<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg42y0jtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gg42y0jtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-move-column-after-ltr" /></template>
