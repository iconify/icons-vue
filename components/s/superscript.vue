<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcxx2abtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jcxx2abtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:superscript" /></template>
