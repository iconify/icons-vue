<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fln_4q79i.css';
import '../../css/m/m3_jbieof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fln_4q79i"/><path class="m3_jbieof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sure-finance" /></template>
