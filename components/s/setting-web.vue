<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6h5_0rkk.css';
import '../../css/b/bad9hsb7u.css';
import '../../css/f/fduciibru.css';
import '../../css/x/xt8o0x15a.css';
import '../../css/t/trmg4pblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="i6h5_0rkk"/><path class="bad9hsb7u"/><circle transform="matrix(0 -1 -1 0 10 14)" class="fduciibru"/><circle transform="matrix(0 -1 -1 0 16 14)" class="fduciibru"/><circle class="xt8o0x15a"/><path class="trmg4pblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:setting-web" /></template>
