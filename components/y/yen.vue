<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhjolt27t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhjolt27t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:yen" /></template>
