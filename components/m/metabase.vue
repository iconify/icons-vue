<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqmbxsbsp.css';
import '../../css/x/xefnkubua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqmbxsbsp"/><path class="xefnkubua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metabase" /></template>
