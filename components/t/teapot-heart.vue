<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou2178jow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou2178jow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:teapot-heart" /></template>
