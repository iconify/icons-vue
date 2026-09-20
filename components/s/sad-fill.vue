<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma4th9pdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma4th9pdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sad-fill" /></template>
