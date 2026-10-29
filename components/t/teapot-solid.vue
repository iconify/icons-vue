<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vz2352biu.css';
import '../../css/b/bn7vl2b9s.css';
import '../../css/g/gna721brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="vz2352biu"/><path class="bn7vl2b9s wm-a"/><path class="gna721brc wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:teapot-solid" /></template>
