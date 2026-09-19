<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzj42ixdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hzj42ixdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nomad-wordmark" /></template>
