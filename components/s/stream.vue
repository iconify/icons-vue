<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/h/huth-8c1f.css';
import '../../css/v/vd4qirmma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="to-5kdesz"><path class="huth-8c1f"/><path class="vd4qirmma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stream" /></template>
