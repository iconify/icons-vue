<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj09plshu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dj09plshu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:onarrowleftright" /></template>
