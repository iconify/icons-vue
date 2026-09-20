<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndbkslbvb.css';
import '../../css/c/cdd4wcvmi.css';
import '../../css/e/eodm2abwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ndbkslbvb"/><path class="cdd4wcvmi"/><path class="eodm2abwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonobarr" /></template>
