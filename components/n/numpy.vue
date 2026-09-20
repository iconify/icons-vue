<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf8g-d54i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf8g-d54i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:numpy" /></template>
