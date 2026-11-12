<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guq7mxbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="guq7mxbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t3-code-dark" /></template>
