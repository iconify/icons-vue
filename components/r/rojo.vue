<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cccyio-9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cccyio-9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rojo" /></template>
