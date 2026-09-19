<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhaol57jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhaol57jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mecha-mask" /></template>
