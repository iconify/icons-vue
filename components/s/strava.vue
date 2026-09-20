<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg6mzf6sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg6mzf6sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:strava" /></template>
