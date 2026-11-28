<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnm_kko2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnm_kko2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:newspaper-star" /></template>
