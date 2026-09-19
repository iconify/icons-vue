<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptkw2rnlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ptkw2rnlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:tumblr" /></template>
