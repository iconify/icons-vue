<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0hexbc2j.css';
import '../../css/h/h447xtb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="o0hexbc2j"/><path class="h447xtb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traccar" /></template>
