<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/m-lwn2brr.css';
import '../../css/h/h2wmdtbnt.css';
import '../../css/b/bxjv56brc.css';
import '../../css/x/xa_7bib3n.css';
import '../../css/z/z_gxk3e6s.css';
import '../../css/e/eyejxqbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="m-lwn2brr wm-deco"/><path class="h2wmdtbnt wm-deco"/><path class="bxjv56brc wm-deco"/><path class="wm-k xa_7bib3n"/><path class="wm-a z_gxk3e6s"/><path class="eyejxqbhe wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:search-x-blueprint" /></template>
