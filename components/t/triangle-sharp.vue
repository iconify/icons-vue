<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2797tbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2797tbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:triangle-sharp" /></template>
