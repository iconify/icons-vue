<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw3x82bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="cw3x82bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tent-arrows-down" /></template>
