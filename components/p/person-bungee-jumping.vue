<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv125nxfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tv125nxfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:person-bungee-jumping" /></template>
