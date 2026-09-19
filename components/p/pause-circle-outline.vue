<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qpyzh0bes.css';
import '../../css/e/e6qicfbfp.css';
import '../../css/i/ih0ctodhf.css';
import '../../css/k/kz0_pvboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qpyzh0bes"/><path class="e6qicfbfp"/><path class="ih0ctodhf"/><path class="kz0_pvboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pause-circle-outline" /></template>
