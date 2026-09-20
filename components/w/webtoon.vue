<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e19wvkb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e19wvkb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:webtoon" /></template>
