<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so0b9bbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="so0b9bbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:sandwich" /></template>
