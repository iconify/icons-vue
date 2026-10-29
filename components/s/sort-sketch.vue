<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f4fq62boi.css';
import '../../css/o/oos9n2b5s.css';
import '../../css/o/oiiu6_b2q.css';
import '../../css/v/va5hn9blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f4fq62boi wm-k"/><path class="oos9n2b5s wm-a"/><path class="oiiu6_b2q wm-k"/><path class="va5hn9blj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sort-sketch" /></template>
