<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wd7ku9bht.css';
import '../../css/p/p111p0b4n.css';
import '../../css/u/u5lsx9bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wd7ku9bht wm-a"/><path class="p111p0b4n wm-k"/><path class="u5lsx9bzl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:text-cursor-sketch" /></template>
