<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moat_y9bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="moat_y9bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:money-bill-1-wave" /></template>
