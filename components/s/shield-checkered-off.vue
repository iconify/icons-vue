<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iezb6eb_v.css';
import '../../css/n/n9eijwbwv.css';
import '../../css/z/zbgn4_-_c.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iezb6eb_v"/><path class="n9eijwbwv"/><path class="zbgn4_-_c"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:shield-checkered-off" /></template>
