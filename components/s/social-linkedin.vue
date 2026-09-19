<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5pvelf5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f5pvelf5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-linkedin" /></template>
