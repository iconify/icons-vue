<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9378k2nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s9378k2nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:sushi-15" /></template>
