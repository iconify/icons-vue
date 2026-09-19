<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awyck1uhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="awyck1uhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:search-location" /></template>
