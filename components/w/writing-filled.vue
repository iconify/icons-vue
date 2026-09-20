<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jusq19xev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jusq19xev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:writing-filled" /></template>
