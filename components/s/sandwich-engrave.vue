<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/utc82s9td.css';
import '../../css/s/sxos2gb0r.css';
import '../../css/w/wqcz8qc_e.css';
import '../../css/x/xac-pkbvl.css';
import '../../css/h/h8wb40b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="utc82s9td wm-k"/><path class="sxos2gb0r wm-a"/><path class="wm-shadow wqcz8qc_e"/><path class="wm-k xac-pkbvl"/><path class="h8wb40b9m wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sandwich-engrave" /></template>
