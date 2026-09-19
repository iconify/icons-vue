<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs2dj5alr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vs2dj5alr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ravendb" /></template>
