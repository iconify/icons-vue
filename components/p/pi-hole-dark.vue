<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oirotweno.css';
import '../../css/d/d9fwxhphv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oirotweno"/><path class="d9fwxhphv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-hole-dark" /></template>
