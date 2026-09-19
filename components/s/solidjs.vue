<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocgohacyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ocgohacyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:solidjs" /></template>
