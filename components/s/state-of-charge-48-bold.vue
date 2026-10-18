<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj-lzbb4z.css';
import '../../css/s/symaru7nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nj-lzbb4z"/><path class="symaru7nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:state-of-charge-48-bold" /></template>
