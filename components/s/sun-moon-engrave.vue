<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fpa8j25-i.css';
import '../../css/p/pm9g_wbfa.css';
import '../../css/b/b5c76ibey.css';
import '../../css/b/btlgwpbsn.css';
import '../../css/z/z6q0xzsvv.css';
import '../../css/q/q08n-4bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fpa8j25-i wm-k"/><path class="pm9g_wbfa wm-a"/><path class="b5c76ibey wm-shadow"/><path class="btlgwpbsn wm-k"/><path class="wm-k z6q0xzsvv"/><path class="q08n-4bjs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sun-moon-engrave" /></template>
