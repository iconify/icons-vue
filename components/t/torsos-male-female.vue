<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofrrycbzm.css';
import '../../css/a/amz2rhbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ofrrycbzm"/><path class="amz2rhbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:torsos-male-female" /></template>
