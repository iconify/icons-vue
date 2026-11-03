<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0z9-6mmj.css';
import '../../css/d/djhg-vbxr.css';
import '../../css/j/j0k4v8zak.css';
import '../../css/c/c4voa1b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r0z9-6mmj"/><path class="djhg-vbxr"/><path class="j0k4v8zak"/><path class="c4voa1b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:phpmyadmin" /></template>
