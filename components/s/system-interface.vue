<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f68_n4bcj.css';
import '../../css/m/mp7nbmbcx.css';
import '../../css/m/m17qjo6op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f68_n4bcj"/><path class="mp7nbmbcx"/><path class="m17qjo6op"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-interface" /></template>
