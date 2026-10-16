<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx4fd5nos.css';
import '../../css/z/zama-11es.css';
import '../../css/y/yvy3k0pml.css';
import '../../css/f/fcme7kbbb.css';
import '../../css/m/me5xyh10x.css';
import '../../css/d/dxxr4jbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xx4fd5nos"/><path class="zama-11es"/><path class="yvy3k0pml"/><path class="fcme7kbbb"/><path class="me5xyh10x"/><path class="dxxr4jbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:turbine-icing-20-bold" /></template>
