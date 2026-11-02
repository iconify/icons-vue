<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8acplbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8acplbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:watering-can-fill" /></template>
