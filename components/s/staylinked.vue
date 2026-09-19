<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbn5-jb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rbn5-jb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:staylinked" /></template>
