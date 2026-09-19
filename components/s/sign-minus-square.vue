<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egnx55p7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egnx55p7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-square" /></template>
