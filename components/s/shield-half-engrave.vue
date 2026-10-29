<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bro8vbcta.css';
import '../../css/s/s84x2zfvv.css';
import '../../css/q/qi8a1ybvv.css';
import '../../css/x/xrfn3bcyz.css';
import '../../css/p/p_jfkcbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bro8vbcta wm-k"/><path class="s84x2zfvv wm-a"/><path class="qi8a1ybvv wm-shadow"/><path class="wm-k xrfn3bcyz"/><path class="p_jfkcbaa wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-half-engrave" /></template>
