<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6y8ptl6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1760,"height":1280};
const content = `<path class="d6y8ptl6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:maxcdn" /></template>
