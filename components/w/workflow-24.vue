<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jga_xuh6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jga_xuh6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:workflow-24" /></template>
