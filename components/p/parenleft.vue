<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4i38ybpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":182,"height":981};
const content = `<path class="e4i38ybpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:parenleft" /></template>
