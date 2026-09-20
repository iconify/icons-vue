<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_ogl0bpc.css';
import '../../css/m/mtxmfcb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_ogl0bpc"/><path class="mtxmfcb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maildev-light" /></template>
