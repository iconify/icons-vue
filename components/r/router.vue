<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx2cbsiiy.css';
import '../../css/u/us9oalb-g.css';
import '../../css/n/n2o677b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xx2cbsiiy"/><path class="us9oalb-g"/><path class="n2o677b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:router" /></template>
