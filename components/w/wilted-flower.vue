<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htej5lsdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="htej5lsdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wilted-flower" /></template>
