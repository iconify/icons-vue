<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5_521b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="q5_521b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:report" /></template>
