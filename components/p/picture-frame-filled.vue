<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7p3bhbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7p3bhbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:picture-frame-filled" /></template>
