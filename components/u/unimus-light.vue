<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un65ooazk.css';
import '../../css/w/wlb9i1ctt.css';
import '../../css/k/kpzxgnq_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="un65ooazk"/><path class="wlb9i1ctt"/><path class="kpzxgnq_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unimus-light" /></template>
