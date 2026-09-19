<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l183q2bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l183q2bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:patreon" /></template>
