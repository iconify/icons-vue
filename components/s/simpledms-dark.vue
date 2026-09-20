<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aifktcb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aifktcb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:simpledms-dark" /></template>
