<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c-ef78b2g.css';
import '../../css/k/ky74_dbht.css';
import '../../css/k/kgfhzmbhl.css';
import '../../css/t/t_1vhibtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c-ef78b2g wm-k"/><path class="ky74_dbht wm-a"/><path class="kgfhzmbhl wm-k"/><path class="t_1vhibtu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shopping-basket-sketch" /></template>
