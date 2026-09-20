<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_294hbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_294hbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teleport-dark" /></template>
