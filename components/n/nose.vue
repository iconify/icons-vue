<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xucuw-bde.css';
import '../../css/y/y8gwbgbko.css';
import '../../css/n/nu3mrp6zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xucuw-bde"/><path class="y8gwbgbko"/><path class="nu3mrp6zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:nose" /></template>
