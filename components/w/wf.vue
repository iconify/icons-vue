<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/f/f-71bdcop.css';
import '../../css/p/pqby8lb2j.css';
import '../../css/g/gdtb-qb5o.css';
import '../../css/p/pmhiyvfve.css';
import '../../css/g/g-shhqb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="f-71bdcop"/><path class="pqby8lb2j"/><path class="gdtb-qb5o"/><path class="pmhiyvfve"/><path class="g-shhqb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:wf" /></template>
