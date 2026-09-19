<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qghqrkb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qghqrkb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:purescript-wordmark" /></template>
