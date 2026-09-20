<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm41kn5-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm41kn5-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:monkey-tie" /></template>
