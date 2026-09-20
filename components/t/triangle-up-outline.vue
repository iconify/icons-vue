<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyvwjobrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hyvwjobrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:triangle-up-outline" /></template>
