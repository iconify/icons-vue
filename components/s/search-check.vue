<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xanb4ubum.css';
import '../../css/n/n-s3_4imp.css';
import '../../css/n/n3murebba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xanb4ubum"/><circle class="n-s3_4imp"/><path class="n3murebba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:search-check" /></template>
