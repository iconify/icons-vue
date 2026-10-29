<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c3ls5nbaa.css';
import '../../css/x/xru6xobqx.css';
import '../../css/e/e-hz-ti3g.css';
import '../../css/y/yeskuobie.css';
import '../../css/p/p70io6b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c3ls5nbaa"/><path class="wm-k xru6xobqx"/><path class="e-hz-ti3g wm-k"/><path class="wm-a yeskuobie"/><path class="p70io6b2r wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:spider-sketch" /></template>
