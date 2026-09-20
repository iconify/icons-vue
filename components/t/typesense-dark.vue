<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muk0_xbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="muk0_xbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typesense-dark" /></template>
