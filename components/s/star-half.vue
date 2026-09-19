<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9o-uhbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="f9o-uhbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:star-half" /></template>
