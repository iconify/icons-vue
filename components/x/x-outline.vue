<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asx97pbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="asx97pbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:x-outline" /></template>
