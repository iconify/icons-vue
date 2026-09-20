<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6bv3cbvb.css';
import '../../css/u/uy6molruc.css';
import '../../css/e/efjg-jbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n6bv3cbvb"/><path class="uy6molruc"/><path class="efjg-jbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reitti" /></template>
