<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw-zpcb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lw-zpcb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:size-emoji-small" /></template>
