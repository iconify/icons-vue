<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvc_zmb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvc_zmb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shape-2-fill" /></template>
