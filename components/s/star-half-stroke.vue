<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxxgum2ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gxxgum2ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:star-half-stroke" /></template>
