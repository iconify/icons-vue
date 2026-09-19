<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1y8fp8ua.css';
import '../../css/l/lm9p31gmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1y8fp8ua"/><path class="lm9p31gmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:terminal-outlined" /></template>
