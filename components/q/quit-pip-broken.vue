<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xnh1ybbye.css';
import '../../css/m/mqszbo63g.css';
import '../../css/d/dmrtm7e_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xnh1ybbye"/><path class="mqszbo63g"/><path class="dmrtm7e_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-pip-broken" /></template>
