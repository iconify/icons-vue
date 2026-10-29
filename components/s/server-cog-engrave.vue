<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rhx_bwhiw.css';
import '../../css/c/cb8204bna.css';
import '../../css/c/cj3o7wbiy.css';
import '../../css/c/cgi6aebyp.css';
import '../../css/j/jes-ovvpz.css';
import '../../css/e/ekmlpmtjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rhx_bwhiw wm-k"/><path class="cb8204bna wm-s"/><path class="cj3o7wbiy wm-shadow"/><path class="cgi6aebyp wm-k"/><path class="jes-ovvpz wm-a"/><path class="ekmlpmtjg wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:server-cog-engrave" /></template>
