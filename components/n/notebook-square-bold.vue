<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjyi8psyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sjyi8psyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-square-bold" /></template>
