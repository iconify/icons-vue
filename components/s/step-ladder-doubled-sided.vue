<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo2gw7byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vo2gw7byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:step-ladder-doubled-sided" /></template>
