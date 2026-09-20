<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8mijlhgj.css';
import '../../css/e/e0vgkpblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8mijlhgj"/><path class="e0vgkpblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-pass-light" /></template>
