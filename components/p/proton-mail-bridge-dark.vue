<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtds4obsx.css';
import '../../css/x/xxyq6_bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtds4obsx"/><path class="xxyq6_bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-mail-bridge-dark" /></template>
