<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy5l9cc_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zy5l9cc_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sulu-wordmark" /></template>
