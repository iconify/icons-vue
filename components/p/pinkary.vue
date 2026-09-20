<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0noxxbmb.css';
import '../../css/y/y46o0xb-b.css';
import '../../css/y/y2vg62bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="s0noxxbmb"/><path class="y46o0xb-b"/><path class="y2vg62bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinkary" /></template>
