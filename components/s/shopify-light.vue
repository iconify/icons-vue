<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpn187_zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jpn187_zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shopify-light" /></template>
