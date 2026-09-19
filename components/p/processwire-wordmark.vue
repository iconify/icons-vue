<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta8kr9snh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ta8kr9snh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:processwire-wordmark" /></template>
