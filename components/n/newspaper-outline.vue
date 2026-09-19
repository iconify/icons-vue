<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmc06hb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmc06hb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:newspaper-outline" /></template>
