<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-hw-5bzi.css';
import '../../css/m/mtxmfcb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-hw-5bzi"/><path class="mtxmfcb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maildev-light" /></template>
