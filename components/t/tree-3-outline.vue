<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgfxdobrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lgfxdobrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-3-outline" /></template>
