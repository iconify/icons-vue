<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwjrr6bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwjrr6bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tag-minus" /></template>
