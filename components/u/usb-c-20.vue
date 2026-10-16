<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7m3inbym.css';
import '../../css/c/cbgy24bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e7m3inbym"/><path class="cbgy24bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:usb-c-20" /></template>
