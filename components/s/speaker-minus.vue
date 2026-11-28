<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjhc1sbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjhc1sbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:speaker-minus" /></template>
