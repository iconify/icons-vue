<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpcptns8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpcptns8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spip-light" /></template>
