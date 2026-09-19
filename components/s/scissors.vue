<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/axw7lr55v.css';
import '../../css/s/sqlr_kgjy.css';
import '../../css/i/inz9m4wmz.css';
import '../../css/d/d741o543y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="axw7lr55v"/><path class="sqlr_kgjy"/><circle class="inz9m4wmz"/><circle class="d741o543y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:scissors" /></template>
