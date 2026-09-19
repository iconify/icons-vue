<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vovp7w37k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vovp7w37k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stackblitz" /></template>
