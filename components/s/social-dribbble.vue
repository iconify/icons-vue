<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmuf1bb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="cmuf1bb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-dribbble" /></template>
