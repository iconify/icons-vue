<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8_gg4bxv.css';
import '../../css/w/wa7uyac8k.css';
import '../../css/t/t7gs68bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8_gg4bxv"/><path class="wa7uyac8k"/><path class="t7gs68bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:wallpaper" /></template>
