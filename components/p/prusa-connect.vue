<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7dfh_bxr.css';
import '../../css/d/doa6wmbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7dfh_bxr"/><path class="doa6wmbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prusa-connect" /></template>
