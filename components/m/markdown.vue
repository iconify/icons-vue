<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3al6s0ue.css';
import '../../css/d/dys46yl0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c3al6s0ue"/><path class="dys46yl0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:markdown" /></template>
