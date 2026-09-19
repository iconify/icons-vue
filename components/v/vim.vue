<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olbm6ob8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="olbm6ob8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vim" /></template>
