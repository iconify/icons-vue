<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysgd0luzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysgd0luzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-lines-fill" /></template>
