<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_eir9x1f.css';
import '../../css/x/xah9mvbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i_eir9x1f"/><path class="xah9mvbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xrsh-dark" /></template>
