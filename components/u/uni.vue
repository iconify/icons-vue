<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zns1uds0y.css';
import '../../css/m/md286fbip.css';
import '../../css/f/fctgmobhd.css';
import '../../css/w/wb8ftfb4k.css';
import '../../css/g/goyzybcsc.css';
import '../../css/r/rjwz6dbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="zns1uds0y"/><g class="md286fbip"><path class="fctgmobhd"/><path class="wb8ftfb4k"/><path class="goyzybcsc"/><path class="rjwz6dbkc"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:uni" /></template>
