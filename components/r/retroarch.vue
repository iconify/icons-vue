<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mebtap2fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mebtap2fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:retroarch" /></template>
