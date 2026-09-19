<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccz98ti9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ccz98ti9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:road-barrier" /></template>
