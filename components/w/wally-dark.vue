<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9v99dbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i9v99dbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wally-dark" /></template>
