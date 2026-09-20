<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_lpyv8on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_lpyv8on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sanity" /></template>
