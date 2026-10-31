<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/fxn87v4vx.css';
import '../../css/t/tz1j7bbth.css';
import '../../css/o/ovnv7qxik.css';
import '../../css/o/oivujhbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="fxn87v4vx wm-shadow"/><path class="tz1j7bbth wm-shadow"/><path class="ovnv7qxik"/><path class="oivujhbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:phone" /></template>
