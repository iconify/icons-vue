<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdrsczb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdrsczb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:podcast-heart" /></template>
