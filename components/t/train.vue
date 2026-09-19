<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw6nvx_mx.css';
import '../../css/c/cbwjarblr.css';
import '../../css/s/sod_7gkfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="iw6nvx_mx"/><circle class="cbwjarblr"/><path class="sod_7gkfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:train" /></template>
