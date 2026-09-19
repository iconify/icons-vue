<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg-uejb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dg-uejb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:today-sharp" /></template>
