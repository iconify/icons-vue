<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqbl-d0dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqbl-d0dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-octagon" /></template>
