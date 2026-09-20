<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw26gsbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw26gsbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-30-fill" /></template>
