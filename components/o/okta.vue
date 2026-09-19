<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtwq637wt.css';
import '../../css/r/rbu9ceb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rtwq637wt"/><path class="rbu9ceb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:okta" /></template>
