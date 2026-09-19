<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm-_2db1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rm-_2db1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:solidjs-wordmark" /></template>
