<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fssbm7fvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":402,"height":512};
const content = `<path class="fssbm7fvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:readthedocs" /></template>
