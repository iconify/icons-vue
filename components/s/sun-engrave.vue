<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xojf8v49t.css';
import '../../css/k/kv0n7fx-i.css';
import '../../css/y/yi23eea4c.css';
import '../../css/t/tg-es2b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xojf8v49t"/><path class="kv0n7fx-i wm-shadow"/><path class="wm-k yi23eea4c"/><path class="tg-es2b-k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sun-engrave" /></template>
