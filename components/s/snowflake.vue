<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjf5pubej.css';
import '../../css/k/kzt1twblh.css';
import '../../css/x/xbxbwdb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjf5pubej"/><path class="kzt1twblh"/><path class="xbxbwdb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:snowflake" /></template>
