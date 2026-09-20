<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm2otvbdc.css';
import '../../css/i/icw3oacuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rm2otvbdc"/><path class="icw3oacuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planka" /></template>
