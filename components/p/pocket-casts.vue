<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieasjfbcb.css';
import '../../css/d/d4shuvlgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ieasjfbcb"/><path class="d4shuvlgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocket-casts" /></template>
