<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbcfokwmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbcfokwmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:stroopwafel-outline" /></template>
