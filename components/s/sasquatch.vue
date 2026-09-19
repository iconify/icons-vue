<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cshrf3fgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cshrf3fgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sasquatch" /></template>
