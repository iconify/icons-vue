<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xa_506f5h.css';
import '../../css/p/pqx2-oyar.css';
import '../../css/z/z9-kayyqj.css';
import '../../css/y/y-maskbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xa_506f5h"/><path class="pqx2-oyar"/><path class="z9-kayyqj"/><path class="y-maskbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-linear" /></template>
