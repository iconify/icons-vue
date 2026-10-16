<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itqentznz.css';
import '../../css/l/l_y65ob0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itqentznz"/><path class="l_y65ob0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:usb-c-20-bold" /></template>
