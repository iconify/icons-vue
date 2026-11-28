<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrk6y7b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrk6y7b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mug-solid" /></template>
