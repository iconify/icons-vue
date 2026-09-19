<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gwf5l3iwb.css';
import '../../css/a/asbceibyx.css';
import '../../css/x/xmr8z2bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gwf5l3iwb"/><circle class="asbceibyx"/><circle class="xmr8z2bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:truck" /></template>
