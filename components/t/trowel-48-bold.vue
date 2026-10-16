<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_9sgybsj.css';
import '../../css/s/sd1bnsbfx.css';
import '../../css/t/teddm1b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s_9sgybsj"/><path class="sd1bnsbfx"/><path class="teddm1b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trowel-48-bold" /></template>
