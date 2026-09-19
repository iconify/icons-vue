<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teanu_nhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":616,"height":512};
const content = `<path class="teanu_nhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:store" /></template>
