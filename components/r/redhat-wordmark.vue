<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8yzh57pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g8yzh57pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:redhat-wordmark" /></template>
