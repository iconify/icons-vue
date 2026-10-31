<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1x_6zbkv.css';
import '../../css/p/pmzzwna2i.css';
import '../../css/n/nxbvtcbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="pmzzwna2i"/><path class="nxbvtcbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:netherlands" /></template>
