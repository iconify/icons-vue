<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw5lxubtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw5lxubtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dot-round" /></template>
