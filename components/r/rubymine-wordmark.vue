<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyo5cmbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gyo5cmbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rubymine-wordmark" /></template>
