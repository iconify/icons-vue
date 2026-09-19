<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udol9rmld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="udol9rmld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:share" /></template>
