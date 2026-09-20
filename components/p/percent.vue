<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/amxs67rqb.css';
import '../../css/t/ty7516ydb.css';
import '../../css/t/t_f65iten.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="amxs67rqb"/><circle class="ty7516ydb"/><circle class="t_f65iten"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:percent" /></template>
