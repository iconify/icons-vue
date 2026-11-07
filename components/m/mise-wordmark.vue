<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0rs67bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c0rs67bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mise-wordmark" /></template>
