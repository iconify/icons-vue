<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtud6knrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wtud6knrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twitch-dark" /></template>
