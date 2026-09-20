<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x0kfgebfc.css';
import '../../css/m/mnqjcr06i.css';
import '../../css/s/sazi09x4s.css';
import '../../css/s/si_mtzbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x0kfgebfc"/><path class="mnqjcr06i"/><path class="sazi09x4s"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plus-minus-broken" /></template>
