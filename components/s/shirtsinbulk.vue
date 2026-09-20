<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi-s5cq-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fi-s5cq-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:shirtsinbulk" /></template>
