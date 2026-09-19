<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvvs-6bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvvs-6bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shapes" /></template>
