<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0ea9lija.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0ea9lija"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:quote" /></template>
