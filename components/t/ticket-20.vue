<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs9-ycc5u.css';
import '../../css/j/j9e98_wlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs9-ycc5u"/><path class="j9e98_wlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ticket-20" /></template>
