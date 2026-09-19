<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxgvn8_0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vxgvn8_0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:mintbit" /></template>
