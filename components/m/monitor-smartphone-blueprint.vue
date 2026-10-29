<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/m1_n6ki3n.css';
import '../../css/a/albw7qb1i.css';
import '../../css/f/f-k5oeq-j.css';
import '../../css/b/b1g1c3bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="m1_n6ki3n wm-k"/><path class="albw7qb1i wm-k"/><path class="f-k5oeq-j wm-a"/><path class="b1g1c3bqc wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:monitor-smartphone-blueprint" /></template>
