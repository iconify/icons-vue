<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg546h7yc.css';
import '../../css/h/h0a-t_-kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg546h7yc"/><path class="h0a-t_-kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:send" /></template>
