<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k019gefpc.css';
import '../../css/f/flgqqpfqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k019gefpc"/><path class="flgqqpfqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:raisedfist" /></template>
