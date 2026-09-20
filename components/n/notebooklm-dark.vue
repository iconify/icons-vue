<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz7386bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iz7386bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notebooklm-dark" /></template>
