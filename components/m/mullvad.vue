<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imprk8tlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imprk8tlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mullvad" /></template>
