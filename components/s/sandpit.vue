<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss0l_dcun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ss0l_dcun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:sandpit" /></template>
