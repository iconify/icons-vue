<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb7cfxups.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nb7cfxups"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:superscript2" /></template>
