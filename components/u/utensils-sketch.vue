<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/by7lzdb6d.css';
import '../../css/i/i-148iksi.css';
import '../../css/g/gmx4ak5hr.css';
import '../../css/x/xj8yknp_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="by7lzdb6d wm-k"/><path class="i-148iksi wm-a"/><path class="gmx4ak5hr wm-k"/><path class="wm-a xj8yknp_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:utensils-sketch" /></template>
