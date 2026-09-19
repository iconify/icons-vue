<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz7g-qohu.css';
import '../../css/x/xafs55bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="lz7g-qohu"/><path class="xafs55bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-mail-unread" /></template>
