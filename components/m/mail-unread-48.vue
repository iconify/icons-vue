<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjbzyzbdn.css';
import '../../css/r/rszikibod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjbzyzbdn"/><path class="rszikibod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-unread-48" /></template>
