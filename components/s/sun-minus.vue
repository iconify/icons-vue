<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgue06l3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgue06l3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sun-minus" /></template>
