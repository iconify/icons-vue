<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djfwacces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djfwacces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-minus" /></template>
