<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_yhajbgl.css';
import '../../css/s/s_tecendb.css';
import '../../css/y/yiybycb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="h_yhajbgl"/><path class="s_tecendb"/><path class="yiybycb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:namespace-outline-alerted" /></template>
