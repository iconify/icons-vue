<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p700io9zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p700io9zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize6" /></template>
