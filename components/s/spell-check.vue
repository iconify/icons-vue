<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_z22dla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gf_z22dla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:spell-check" /></template>
