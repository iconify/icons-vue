<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwg6h_bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwg6h_bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-pin-2" /></template>
