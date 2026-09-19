<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncqz1lymk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ncqz1lymk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal" /></template>
