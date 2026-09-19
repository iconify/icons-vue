<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdjyr7bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="cdjyr7bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:yelp" /></template>
