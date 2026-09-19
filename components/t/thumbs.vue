<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev-b95nln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":720,"height":780};
const content = `<path class="ev-b95nln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:thumbs" /></template>
