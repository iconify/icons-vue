<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/i/i4xydol5b.css';
import '../../css/c/c9yt0g5nq.css';
import '../../css/s/s04bc1zdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="i4xydol5b"/><path class="c9yt0g5nq"/><path class="s04bc1zdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ws-1x1" /></template>
