<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pkxx7pbdp.css';
import '../../css/h/hp_pc2tmb.css';
import '../../css/t/tmnkdvnlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="pkxx7pbdp"/><path class="hp_pc2tmb"/><path class="tmnkdvnlf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-vertical-outline" /></template>
