<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg76_7bbe.css';
import '../../css/m/m0b8pab-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer eg76_7bbe"/><path class="duoicon-secondary-layer m0b8pab-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:toggle" /></template>
