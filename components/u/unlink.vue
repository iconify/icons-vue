<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8h4abdke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8h4abdke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:unlink" /></template>
