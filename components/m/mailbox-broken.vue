<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sdeke6b0d.css';
import '../../css/r/rkj4y3bbx.css';
import '../../css/c/c9nmvl4gm.css';
import '../../css/a/afxlu6cvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sdeke6b0d"/><path class="rkj4y3bbx"/><path class="c9nmvl4gm"/><path class="afxlu6cvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mailbox-broken" /></template>
