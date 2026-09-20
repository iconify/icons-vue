<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy08vwban.css';
import '../../css/h/hx5mj141a.css';
import '../../css/q/qxcq365rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy08vwban"/><path class="hx5mj141a"/><path class="qxcq365rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-box-solid" /></template>
