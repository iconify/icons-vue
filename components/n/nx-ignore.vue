<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixmy2_bju.css';
import '../../css/a/al6kmgb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ixmy2_bju"/><path class="al6kmgb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nx-ignore" /></template>
