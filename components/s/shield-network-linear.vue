<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/eu5pm3tfm.css';
import '../../css/r/r5fahkzon.css';
import '../../css/g/g7hqkcb6k.css';
import '../../css/t/tokx6ighc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eu5pm3tfm"/><path class="r5fahkzon"/><path class="g7hqkcb6k"/><path class="tokx6ighc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-network-linear" /></template>
