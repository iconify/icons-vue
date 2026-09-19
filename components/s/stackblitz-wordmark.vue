<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd1lu708s.css';
import '../../css/g/gmbi57b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sd1lu708s"/><path class="gmbi57b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stackblitz-wordmark" /></template>
