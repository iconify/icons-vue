<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puv6w158o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="puv6w158o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:replit-wordmark" /></template>
