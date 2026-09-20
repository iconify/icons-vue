<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy0upab9n.css';
import '../../css/l/lyrgvcbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vy0upab9n"/><path class="lyrgvcbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:reason" /></template>
