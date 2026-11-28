<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnva-97fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnva-97fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:thumbs-up" /></template>
