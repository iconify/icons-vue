<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr92bcb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hr92bcb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:twitter-alt" /></template>
