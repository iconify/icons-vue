<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glsz6lb6o.css';
import '../../css/l/lkhxdccgi.css';
import '../../css/d/d29tb6b3e.css';
import '../../css/t/t0vmepbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="glsz6lb6o"/><path class="lkhxdccgi"/><path class="d29tb6b3e"/><path class="t0vmepbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mosque-20" /></template>
