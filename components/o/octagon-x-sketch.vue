<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rlqc2tblo.css';
import '../../css/b/b50d454iu.css';
import '../../css/y/ykharcboa.css';
import '../../css/l/lp5-t8f8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rlqc2tblo"/><path class="b50d454iu wm-a"/><path class="wm-k ykharcboa"/><path class="lp5-t8f8t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:octagon-x-sketch" /></template>
