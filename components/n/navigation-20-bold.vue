<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpzke5o9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wpzke5o9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:navigation-20-bold" /></template>
