<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dir6rysvf.css';
import '../../css/a/ab03k5swc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dir6rysvf"/><path class="ab03k5swc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rsshub-dark" /></template>
