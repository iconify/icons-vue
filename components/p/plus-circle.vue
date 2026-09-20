<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk63d0d6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="pk63d0d6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:plus-circle" /></template>
