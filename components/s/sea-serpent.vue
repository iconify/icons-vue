<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yihu4wbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yihu4wbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sea-serpent" /></template>
