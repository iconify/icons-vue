<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jngitaclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jngitaclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pallet" /></template>
