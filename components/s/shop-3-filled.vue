<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq7ufdtte.css';
import '../../css/j/jb-34lb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq7ufdtte"/><path class="jb-34lb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shop-3-filled" /></template>
