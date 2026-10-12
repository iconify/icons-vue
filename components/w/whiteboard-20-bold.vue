<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apx8esb2g.css';
import '../../css/q/qz-yjjbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="apx8esb2g"/><path class="qz-yjjbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whiteboard-20-bold" /></template>
