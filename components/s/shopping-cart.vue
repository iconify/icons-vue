<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc06xoozo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gc06xoozo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shopping-cart" /></template>
