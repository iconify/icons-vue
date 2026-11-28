<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sazs_obtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sazs_obtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:newspaper-star" /></template>
