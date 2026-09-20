<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m92zj5l4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m92zj5l4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:myspace" /></template>
