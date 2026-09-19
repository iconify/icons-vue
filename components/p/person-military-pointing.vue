<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plp-_mbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="plp-_mbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-military-pointing" /></template>
