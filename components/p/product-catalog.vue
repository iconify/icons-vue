<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8018i56a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8018i56a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:product-catalog" /></template>
