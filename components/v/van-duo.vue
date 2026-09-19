<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n4-tzzbmd.css';
import '../../css/z/z_lgxqp8u.css';
import '../../css/t/ttsnun36c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="n4-tzzbmd"/><path class="z_lgxqp8u"/><path class="ttsnun36c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:van-duo" /></template>
