<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdrk782lf.css';
import '../../css/d/d5j3t7b4j.css';
import '../../css/k/kz4o5-4xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdrk782lf wm-k"/><path class="d5j3t7b4j wm-a"/><path class="kz4o5-4xv wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:message-square-text" /></template>
