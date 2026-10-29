<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b7kyjwrad.css';
import '../../css/p/p2z9olxff.css';
import '../../css/e/eoiz0rolg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b7kyjwrad"/><path class="p2z9olxff wm-a"/><path class="eoiz0rolg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-duo" /></template>
