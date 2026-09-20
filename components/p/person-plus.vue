<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/x/xn4903-ui.css';
import '../../css/w/w7m3uccqr.css';
import '../../css/w/wl50mf2jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="xn4903-ui"/><path class="w7m3uccqr"/><path class="wl50mf2jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:person-plus" /></template>
