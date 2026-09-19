<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njjyxzbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njjyxzbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:ordered-list-outline" /></template>
