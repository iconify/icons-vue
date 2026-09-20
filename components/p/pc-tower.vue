<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3ge_6bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3ge_6bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pc-tower" /></template>
