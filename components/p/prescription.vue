<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnfh_24gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="pnfh_24gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:prescription" /></template>
