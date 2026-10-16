<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8r--tbbc.css';
import '../../css/n/ni0ydvbwi.css';
import '../../css/m/mswb4uy9b.css';
import '../../css/t/tm4h_tz1k.css';
import '../../css/v/v135c1b7p.css';
import '../../css/u/u8ws8ibhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750.11,"height":189.77};
const content = `<path class="b8r--tbbc"/><path class="ni0ydvbwi"/><path class="mswb4uy9b"/><path class="tm4h_tz1k"/><path class="v135c1b7p"/><path class="u8ws8ibhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:orangehrm" /></template>
