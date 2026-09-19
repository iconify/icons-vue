<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by7yhws7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="by7yhws7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:zed" /></template>
