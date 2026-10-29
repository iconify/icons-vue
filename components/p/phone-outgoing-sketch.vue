<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w328ithck.css';
import '../../css/d/dqwndkx9y.css';
import '../../css/q/ql7xkx99v.css';
import '../../css/l/lwpbxcrve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w328ithck"/><path class="dqwndkx9y wm-s"/><path class="ql7xkx99v wm-k"/><path class="lwpbxcrve wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-outgoing-sketch" /></template>
