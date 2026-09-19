<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4j9h4bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="q4j9h4bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:time" /></template>
