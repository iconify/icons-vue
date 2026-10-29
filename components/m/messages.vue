<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc5hd6b6e.css';
import '../../css/i/iepl1qnjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc5hd6b6e"/><path class="iepl1qnjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:messages" /></template>
