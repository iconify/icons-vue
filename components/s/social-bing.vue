<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8e3o6bwj.css';
import '../../css/r/r0h4debhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<ellipse class="q8e3o6bwj"/><path class="r0h4debhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-bing" /></template>
