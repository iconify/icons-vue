<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl6s_972s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tl6s_972s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:telefrag" /></template>
