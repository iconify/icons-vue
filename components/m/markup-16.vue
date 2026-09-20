<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_0nci75d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l_0nci75d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:markup-16" /></template>
