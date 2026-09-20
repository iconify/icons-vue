<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fziy_koug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fziy_koug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sunglasses" /></template>
