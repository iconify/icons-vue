<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/o8x38jbfa.css';
import '../../css/d/dkf_gz6kq.css';
import '../../css/c/czqpd_v7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="o8x38jbfa"/><circle class="dkf_gz6kq"/><path class="czqpd_v7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:people-bottom-card" /></template>
