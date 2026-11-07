<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogd2nrbqw.css';
import '../../css/i/i2rrj-bgy.css';
import '../../css/a/amjowyqts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogd2nrbqw"/><path class="i2rrj-bgy"/><path clip-rule="evenodd" class="amjowyqts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-rotate-bold" /></template>
