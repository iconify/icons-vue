<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsu17feyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lsu17feyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mobile-phone-with-keypad-and-antenna-beside-mobile-phone-with-touchscreen-and-antenna" /></template>
