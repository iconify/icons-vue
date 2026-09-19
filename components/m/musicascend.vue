<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng037rl3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ng037rl3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:musicascend" /></template>
