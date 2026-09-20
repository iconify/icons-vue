<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oynqdsb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":368};
const content = `<path class="oynqdsb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stackblitz" /></template>
