<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrlw-04kw.css';
import '../../css/l/l3azjz_az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrlw-04kw"/><path class="l3azjz_az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:saltcorn-dark" /></template>
