<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx43in0lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx43in0lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-bold" /></template>
