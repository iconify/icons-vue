<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibjkizgjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ibjkizgjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:parseable" /></template>
