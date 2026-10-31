<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1x_6zbkv.css';
import '../../css/y/y55zcjfsz.css';
import '../../css/o/ozhv1qh5i.css';
import '../../css/i/imje9zb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="y55zcjfsz"/><path class="ozhv1qh5i"/><path class="imje9zb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:palestine" /></template>
