<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uio6rac6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uio6rac6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:send" /></template>
