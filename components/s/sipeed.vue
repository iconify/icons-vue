<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rld-_ccic.css';
import '../../css/v/vl74ao08p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rld-_ccic"/><path class="vl74ao08p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sipeed" /></template>
