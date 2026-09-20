<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8chphb8w.css';
import '../../css/k/kpuc3bbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l8chphb8w"/><path clip-rule="evenodd" class="kpuc3bbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:select-all-16" /></template>
