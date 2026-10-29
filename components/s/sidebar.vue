<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ousr7gb-s.css';
import '../../css/j/j4j_tvbpu.css';
import '../../css/s/sof-_6mix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ousr7gb-s"/><path class="j4j_tvbpu"/><path class="sof-_6mix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sidebar" /></template>
