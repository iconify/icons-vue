<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vkgfvu33e.css';
import '../../css/s/sm3wc3-js.css';
import '../../css/s/sych0xh2d.css';
import '../../css/a/aap5atbkv.css';
import '../../css/s/s8-jh0bvg.css';
import '../../css/r/r4k-9nyuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vkgfvu33e wm-k"/><path class="sm3wc3-js wm-a"/><path class="sych0xh2d wm-shadow"/><path class="aap5atbkv wm-k"/><path class="s8-jh0bvg wm-a"/><path class="r4k-9nyuf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mails-engrave" /></template>
