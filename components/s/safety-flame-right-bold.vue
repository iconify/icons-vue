<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4uwu0-hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4uwu0-hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:safety-flame-right-bold" /></template>
