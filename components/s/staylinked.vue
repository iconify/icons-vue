<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjlxl3bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":512};
const content = `<path class="fjlxl3bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:staylinked" /></template>
