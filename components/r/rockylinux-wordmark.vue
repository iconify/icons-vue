<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvjhj9bjg.css';
import '../../css/j/jpru1cc9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mvjhj9bjg"/><path class="jpru1cc9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rockylinux-wordmark" /></template>
