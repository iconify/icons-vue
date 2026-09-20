<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfo6y1b6f.css';
import '../../css/s/sflhpq2ep.css';
import '../../css/d/dy0pnwb7i.css';
import '../../css/a/abbea4hvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<path class="zfo6y1b6f"/><path class="sflhpq2ep"/><path class="dy0pnwb7i"/><path class="abbea4hvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:preact" /></template>
