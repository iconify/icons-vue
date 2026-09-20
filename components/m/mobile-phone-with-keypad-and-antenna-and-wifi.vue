<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy-cs117v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iy-cs117v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mobile-phone-with-keypad-and-antenna-and-wifi" /></template>
