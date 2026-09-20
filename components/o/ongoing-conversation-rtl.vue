<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbe0iemxf.css';
import '../../css/t/tiglpdb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hbe0iemxf"/><path class="tiglpdb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:ongoing-conversation-rtl" /></template>
