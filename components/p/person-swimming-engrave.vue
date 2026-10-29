<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dp_w_pbja.css';
import '../../css/a/axfn2s2ey.css';
import '../../css/b/b403txfow.css';
import '../../css/f/fb_n1soxb.css';
import '../../css/n/nt61q7bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dp_w_pbja wm-k"/><path class="axfn2s2ey wm-a"/><path class="b403txfow wm-shadow"/><path class="fb_n1soxb wm-k"/><path class="nt61q7bou wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:person-swimming-engrave" /></template>
