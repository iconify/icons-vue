<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyx1o4bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cyx1o4bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-gitlab" /></template>
