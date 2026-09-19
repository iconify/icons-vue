<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggfdt95ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ggfdt95ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:rew" /></template>
