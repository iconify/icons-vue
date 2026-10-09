<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrk88uxja.css';
import '../../css/y/y9dqkpbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="y9dqkpbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terminal-square-48-bold" /></template>
