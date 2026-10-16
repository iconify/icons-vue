<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m808873ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m808873ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tsunami-20-bold" /></template>
