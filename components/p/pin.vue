<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8uv07bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8uv07bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:pin" /></template>
