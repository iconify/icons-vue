<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3-oi6oyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="c3-oi6oyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:restaurant-pizza-11" /></template>
