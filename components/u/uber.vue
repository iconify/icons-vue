<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jon1cz6hx.css';
import '../../css/l/lv3b0kbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jon1cz6hx"/><path class="lv3b0kbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uber" /></template>
