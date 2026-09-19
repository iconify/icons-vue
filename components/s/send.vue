<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6gpzfb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6gpzfb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:send" /></template>
