<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v--3-qaeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v--3-qaeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomskitchen" /></template>
