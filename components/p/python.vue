<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrbwxfd2d.css';
import '../../css/h/h697m9a0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrbwxfd2d"/><path class="h697m9a0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:python" /></template>
