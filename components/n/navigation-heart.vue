<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tah6431yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tah6431yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-heart" /></template>
