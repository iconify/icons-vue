<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzganq2ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qzganq2ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:oxygen-tank" /></template>
