<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryxl_tbum.css';
import '../../css/x/xka5jqons.css';
import '../../css/x/x7iitf4_b.css';
import '../../css/o/o8wlliifz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ryxl_tbum"/><path class="xka5jqons"/><path class="x7iitf4_b"/><path class="o8wlliifz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:qwik-wordmark" /></template>
