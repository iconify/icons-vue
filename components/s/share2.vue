<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr51um7au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kr51um7au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:share2" /></template>
