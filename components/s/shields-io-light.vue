<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un47udnvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="un47udnvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shields-io-light" /></template>
