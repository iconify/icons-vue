<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn2z21zcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jn2z21zcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:neon" /></template>
