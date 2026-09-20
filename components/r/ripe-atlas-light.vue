<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpxhnwrkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpxhnwrkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ripe-atlas-light" /></template>
