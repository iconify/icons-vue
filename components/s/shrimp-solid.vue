<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftzkzib_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftzkzib_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shrimp-solid" /></template>
