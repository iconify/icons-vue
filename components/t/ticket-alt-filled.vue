<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1q3vjbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1q3vjbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ticket-alt-filled" /></template>
