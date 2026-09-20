<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yukzw5bvx.css';
import '../../css/z/z_i2eab6l.css';
import '../../css/o/ojyjyhb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yukzw5bvx"/><rect class="z_i2eab6l"/><path class="ojyjyhb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:picture-in-picture-enter" /></template>
