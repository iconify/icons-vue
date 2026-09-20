<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/l/l8tiy2eeu.css';
import '../../css/n/n1j1stbmb.css';
import '../../css/j/j7jrpp0bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="l8tiy2eeu"/><path class="n1j1stbmb"/><path class="j7jrpp0bb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sms-edit" /></template>
