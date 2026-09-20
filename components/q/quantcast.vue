<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dle73-aae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dle73-aae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:quantcast" /></template>
