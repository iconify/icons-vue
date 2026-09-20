<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt7r1cbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt7r1cbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-solid" /></template>
