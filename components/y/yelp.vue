<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn9_2bcqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn9_2bcqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:yelp" /></template>
