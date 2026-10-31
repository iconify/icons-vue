<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/at2izmb5l.css';
import '../../css/l/lvmg8g6js.css';
import '../../css/h/hta33-9ph.css';
import '../../css/p/ps6gdacnv.css';
import '../../css/t/tsa3egbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="at2izmb5l wm-shadow"/><path class="lvmg8g6js wm-shadow"/><path class="hta33-9ph"/><path class="ps6gdacnv"/><path class="tsa3egbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:thermometer-snowflake" /></template>
