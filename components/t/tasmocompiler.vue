<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xghsn32in.css';
import '../../css/h/hjo06mb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xghsn32in"/><path class="hjo06mb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tasmocompiler" /></template>
