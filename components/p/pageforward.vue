<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlcm14syu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jlcm14syu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pageforward" /></template>
