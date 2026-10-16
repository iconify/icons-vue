<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgjp5_b_u.css';
import '../../css/h/hdf3k4bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="hdf3k4bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-gas-20" /></template>
