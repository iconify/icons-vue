<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecbob4veg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecbob4veg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smartwatch" /></template>
