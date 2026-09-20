<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs4ystbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qs4ystbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:mast-communications-14" /></template>
