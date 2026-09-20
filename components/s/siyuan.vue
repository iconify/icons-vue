<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7020pbgf.css';
import '../../css/p/p-fy8svxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7020pbgf"/><path class="p-fy8svxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:siyuan" /></template>
