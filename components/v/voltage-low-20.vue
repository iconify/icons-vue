<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlwbi4p-v.css';
import '../../css/f/f_y7kz9fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vlwbi4p-v"/><path class="f_y7kz9fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-low-20" /></template>
