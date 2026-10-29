<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyl5x0xhs.css';
import '../../css/u/udu2-jboo.css';
import '../../css/i/i0745hb7h.css';
import '../../css/x/xl1d1vb_i.css';
import '../../css/u/ubf44wbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k xyl5x0xhs"/><path class="udu2-jboo wm-a"/><path class="i0745hb7h wm-a"/><path class="wm-a xl1d1vb_i"/><path class="ubf44wbel wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:qr-code" /></template>
