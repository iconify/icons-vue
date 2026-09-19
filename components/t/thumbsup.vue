<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huwky1bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="huwky1bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thumbsup" /></template>
