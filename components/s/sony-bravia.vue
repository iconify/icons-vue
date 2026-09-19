<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdupibcdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdupibcdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sony-bravia" /></template>
