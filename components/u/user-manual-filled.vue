<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkibg5b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qkibg5b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-manual-filled" /></template>
