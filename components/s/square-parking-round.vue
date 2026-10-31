<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz04stxdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz04stxdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-parking-round" /></template>
