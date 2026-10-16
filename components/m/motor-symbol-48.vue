<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbksdfbgm.css';
import '../../css/v/vkqyuvbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qbksdfbgm"/><path class="vkqyuvbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:motor-symbol-48" /></template>
