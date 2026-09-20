<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv0sy5bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv0sy5bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-list" /></template>
