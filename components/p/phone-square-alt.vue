<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfxmpcb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mfxmpcb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:phone-square-alt" /></template>
