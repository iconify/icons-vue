<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w25egcbny.css';
import '../../css/e/egmsjwuap.css';
import '../../css/q/qcorjrvgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w25egcbny"/><path class="egmsjwuap"/><path class="qcorjrvgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whiteheavycheckmark" /></template>
