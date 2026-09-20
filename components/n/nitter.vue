<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs4b4obfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xs4b4obfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nitter" /></template>
