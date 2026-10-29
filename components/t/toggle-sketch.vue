<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gi6w2mh5t.css';
import '../../css/i/i7vap8bao.css';
import '../../css/r/r49sd0bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gi6w2mh5t"/><path class="i7vap8bao wm-k"/><circle class="r49sd0bbi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toggle-sketch" /></template>
