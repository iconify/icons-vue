<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o58hkebvg.css';
import '../../css/g/g2f1i4b_f.css';
import '../../css/r/r1gnjem7y.css';
import '../../css/y/yr0pp4b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="o58hkebvg"><path class="g2f1i4b_f"/><path class="r1gnjem7y"/><path class="yr0pp4b7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:reminder-ribbon" /></template>
