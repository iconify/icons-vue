<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gu943ccdr.css';
import '../../css/i/it7nrybuq.css';
import '../../css/d/dzd7g3bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gu943ccdr"/><path class="it7nrybuq"/><path class="dzd7g3bgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sushi-02" /></template>
