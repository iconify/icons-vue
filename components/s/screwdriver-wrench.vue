<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmlkhtbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pmlkhtbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:screwdriver-wrench" /></template>
