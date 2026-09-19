<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q514pqbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q514pqbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:move-to-folder" /></template>
