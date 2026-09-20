<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bov0584ws.css';
import '../../css/u/u6f-okb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bov0584ws"/><path class="u6f-okb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openai" /></template>
