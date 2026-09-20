<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amgx-8bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amgx-8bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:microphone-off" /></template>
