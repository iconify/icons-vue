<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amcaz4b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="amcaz4b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:waxing-gibbous-moon-symbol" /></template>
