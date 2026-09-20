<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxf5f-bxr.css';
import '../../css/j/jb9pwtbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxf5f-bxr"/><path clip-rule="evenodd" class="jb9pwtbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:message-3-text" /></template>
