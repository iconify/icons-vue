<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tlhbmhath.css';
import '../../css/o/oh_bc-b9h.css';
import '../../css/p/phgew-92f.css';
import '../../css/b/b4mz9pbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tlhbmhath"/><path class="oh_bc-b9h wm-k"/><path class="phgew-92f wm-k"/><path class="b4mz9pbbf wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-star-sketch" /></template>
