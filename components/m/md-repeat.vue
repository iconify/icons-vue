<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi1xhtbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fi1xhtbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-repeat" /></template>
