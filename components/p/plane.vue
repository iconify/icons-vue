<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m52xe297f.css';
import '../../css/q/qdp4kbckc.css';
import '../../css/y/y3mtozbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m52xe297f"/><path class="qdp4kbckc"/><path class="y3mtozbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:plane" /></template>
