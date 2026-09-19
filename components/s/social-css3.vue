<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0v4h2v6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0v4h2v6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-css3" /></template>
