<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjms-oqvl.css';
import '../../css/v/v2tmeobir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjms-oqvl"/><path class="v2tmeobir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-minus-filled" /></template>
