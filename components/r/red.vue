<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az40pwb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="az40pwb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:red" /></template>
