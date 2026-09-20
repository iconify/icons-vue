<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrzww_a4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrzww_a4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nubank" /></template>
