<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr8qrx7dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wr8qrx7dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:store-outline" /></template>
