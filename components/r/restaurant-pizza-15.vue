<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqlqe17_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mqlqe17_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:restaurant-pizza-15" /></template>
