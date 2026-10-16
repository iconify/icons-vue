<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_pz37b4w.css';
import '../../css/u/u-jkgcbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u_pz37b4w"/><path class="u-jkgcbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticker-48-bold" /></template>
