<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0-gr6bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q0-gr6bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:options-vertical" /></template>
