<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5x8pirvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u5x8pirvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:tor-browser" /></template>
