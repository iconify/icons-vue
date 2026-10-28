<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghd80rlpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghd80rlpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:upload" /></template>
