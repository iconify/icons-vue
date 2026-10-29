<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s_b4-ibdg.css';
import '../../css/l/l1o1jw0fj.css';
import '../../css/f/fs-ghbbgv.css';
import '../../css/j/jeo1kfb-t.css';
import '../../css/c/ccsoahs3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s_b4-ibdg wm-k"/><path class="l1o1jw0fj wm-a"/><path class="fs-ghbbgv wm-shadow"/><path class="jeo1kfb-t wm-k"/><path class="ccsoahs3k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:superscript-engrave" /></template>
