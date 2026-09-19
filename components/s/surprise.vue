<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt6-q7b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="dt6-q7b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:surprise" /></template>
