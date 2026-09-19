<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-xlhab4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g-xlhab4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-medium" /></template>
