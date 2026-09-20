<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/iw4gmnxtx.css';
import '../../css/m/m0iv8zt0r.css';
import '../../css/l/lcyumsbfg.css';
import '../../css/z/zyj4joh2r.css';
import '../../css/v/vmj8f58-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="iw4gmnxtx"/><path class="m0iv8zt0r"/><path class="lcyumsbfg"/><path class="zyj4joh2r"/><path class="vmj8f58-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wireless-house-signal" /></template>
