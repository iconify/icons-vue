<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1_i6mbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k1_i6mbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:powerdns-light" /></template>
