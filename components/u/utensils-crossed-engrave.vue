<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mv35mk_ha.css';
import '../../css/v/vfnwcz4tm.css';
import '../../css/e/e57-ksbzo.css';
import '../../css/b/b5jgdnp5j.css';
import '../../css/t/t8rq8gxbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mv35mk_ha wm-k"/><path class="vfnwcz4tm wm-a"/><path class="e57-ksbzo wm-shadow"/><path class="b5jgdnp5j wm-k"/><path class="t8rq8gxbc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:utensils-crossed-engrave" /></template>
