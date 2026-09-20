<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmgslx9mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="zmgslx9mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:triangle-stroked-11" /></template>
