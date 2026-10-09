<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtk7136by.css';
import '../../css/i/i3cagyb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qtk7136by"/><path class="i3cagyb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-48" /></template>
