<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6btxnbno.css';
import '../../css/o/o8-mnxbkx.css';
import '../../css/g/gv6b2xb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24.9,"height":28};
const content = `<g class="m6btxnbno"><path class="o8-mnxbkx"/><path class="gv6b2xb3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sonojs" /></template>
