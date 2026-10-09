<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wune1aczr.css';
import '../../css/g/gwm8q7b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wune1aczr"/><path class="gwm8q7b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rolling-pin-48" /></template>
