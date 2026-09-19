<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pji5ilgek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="pji5ilgek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:toys" /></template>
