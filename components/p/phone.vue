<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6h50v71y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6h50v71y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:phone" /></template>
