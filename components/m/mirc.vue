<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-0m7-b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-0m7-b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mirc" /></template>
