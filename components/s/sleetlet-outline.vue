<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnt5_6bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hnt5_6bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sleetlet-outline" /></template>
