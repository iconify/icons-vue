<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic_al5yga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic_al5yga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:octopus" /></template>
