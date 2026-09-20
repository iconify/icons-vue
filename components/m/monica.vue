<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v822w46ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v822w46ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:monica" /></template>
