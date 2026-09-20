<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gpuw72fip.css';
import '../../css/k/kl7dgmbhv.css';
import '../../css/f/fk2z6voyg.css';
import '../../css/t/t03t62bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gpuw72fip"/><path class="kl7dgmbhv"/><path class="fk2z6voyg"/><path class="t03t62bhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:map-location-flat" /></template>
