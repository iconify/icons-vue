<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dir5a1bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dir5a1bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:options" /></template>
