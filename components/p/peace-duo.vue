<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yo2whbr3a.css';
import '../../css/t/tm5i3nbcx.css';
import '../../css/u/un4u8-1xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="yo2whbr3a"/><path class="tm5i3nbcx"/><path class="un4u8-1xm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:peace-duo" /></template>
