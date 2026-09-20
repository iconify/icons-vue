<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulve3il0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ulve3il0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pango-light" /></template>
