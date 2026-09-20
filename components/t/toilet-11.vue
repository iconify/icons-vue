<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsbayybja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="zsbayybja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:toilet-11" /></template>
