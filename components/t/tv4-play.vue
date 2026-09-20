<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sscfj9bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sscfj9bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tv4-play" /></template>
