<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg588xblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gg588xblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:star-filled-16" /></template>
