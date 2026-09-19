<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwe5dkr3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwe5dkr3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thumbs-down" /></template>
