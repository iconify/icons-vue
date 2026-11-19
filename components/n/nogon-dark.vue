<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5m7ms6tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5m7ms6tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nogon-dark" /></template>
