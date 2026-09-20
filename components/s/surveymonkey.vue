<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1fb5gb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1fb5gb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:surveymonkey" /></template>
