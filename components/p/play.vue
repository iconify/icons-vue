<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsgs6gbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsgs6gbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:play" /></template>
