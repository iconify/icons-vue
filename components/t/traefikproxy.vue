<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3794mo3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f3794mo3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:traefikproxy" /></template>
