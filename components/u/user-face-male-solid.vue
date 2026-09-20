<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umr1td1ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="umr1td1ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-face-male-solid" /></template>
