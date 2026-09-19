<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/o/ozxwspm0a.css';
import '../../css/o/ouf_zdbvd.css';
import '../../css/d/d3_lg_bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="ozxwspm0a"/><path class="ouf_zdbvd"/><path class="d3_lg_bwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:producer-portal" /></template>
