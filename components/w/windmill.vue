<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk1fx-k4e.css';
import '../../css/g/gt8biccrk.css';
import '../../css/k/kg64bdngn.css';
import '../../css/w/wihudhbam.css';
import '../../css/s/si8zw661w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="tk1fx-k4e"><path class="gt8biccrk"/><path class="kg64bdngn"/><path class="wihudhbam"/><path class="si8zw661w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:windmill" /></template>
