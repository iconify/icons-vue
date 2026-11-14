<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlnx_8bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlnx_8bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:mute" /></template>
