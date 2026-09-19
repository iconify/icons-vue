<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j7dfqjbmm.css';
import '../../css/m/md286fbip.css';
import '../../css/m/mnclqej_r.css';
import '../../css/t/t78b-pbku.css';
import '../../css/n/nvrchz51g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="j7dfqjbmm"/><g transform="translate(5 5)" class="md286fbip"><path class="mnclqej_r"/><circle class="t78b-pbku"/><path class="nvrchz51g"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:ong" /></template>
