<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pffvbac1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pffvbac1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:square-root-alt" /></template>
