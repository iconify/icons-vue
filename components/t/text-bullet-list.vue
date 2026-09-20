<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aoexxpy5g.css';
import '../../css/l/l_kvvrcsk.css';
import '../../css/p/p3hadrdis.css';
import '../../css/f/f-9on35bf.css';
import '../../css/m/mqk48md2c.css';
import '../../css/c/cn5ff8b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="aoexxpy5g"/><path class="l_kvvrcsk"/><circle class="p3hadrdis"/><path class="f-9on35bf"/><circle class="mqk48md2c"/><path class="cn5ff8b6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-bullet-list" /></template>
