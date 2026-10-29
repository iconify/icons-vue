<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cqhiobchy.css';
import '../../css/r/rzd01oq5r.css';
import '../../css/h/hbz3scbjd.css';
import '../../css/t/tsgnk6b9n.css';
import '../../css/p/p77vdobsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cqhiobchy wm-k"/><path class="rzd01oq5r wm-a"/><path class="hbz3scbjd wm-shadow"/><path class="tsgnk6b9n wm-k"/><path class="p77vdobsr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:settings-2-engrave" /></template>
