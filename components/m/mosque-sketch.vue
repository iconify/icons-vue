<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w5wcaxskk.css';
import '../../css/x/xlcd5qbeq.css';
import '../../css/d/d-tr2fb7r.css';
import '../../css/i/ii_20en4n.css';
import '../../css/j/jv10pq-vg.css';
import '../../css/a/ankdckbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w5wcaxskk wm-k"/><path class="wm-a xlcd5qbeq"/><path class="d-tr2fb7r wm-s"/><path class="ii_20en4n wm-k"/><path class="jv10pq-vg wm-a"/><path class="ankdckbvk wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mosque-sketch" /></template>
