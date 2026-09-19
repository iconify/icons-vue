<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjm6dccxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kjm6dccxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:snowflake-outline" /></template>
