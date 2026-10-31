<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1x_6zbkv.css';
import '../../css/d/dz--kkbng.css';
import '../../css/n/ndsoh9bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="dz--kkbng"/><path class="ndsoh9bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:yemen" /></template>
