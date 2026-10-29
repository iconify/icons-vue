<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvh4r_b8g.css';
import '../../css/d/dt926jbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvh4r_b8g wm-k"/><path class="dt926jbqr wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:undo" /></template>
