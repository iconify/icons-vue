<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/x/xdwzsgdrd.css';
import '../../css/f/fnomx0bsr.css';
import '../../css/d/dajmntbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow xdwzsgdrd"/><path class="fnomx0bsr wm-shadow"/><path class="dajmntbuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:move" /></template>
