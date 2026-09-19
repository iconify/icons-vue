<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y19ixtbyb.css';
import '../../css/r/r_go1j2mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y19ixtbyb"/><path class="r_go1j2mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:xd" /></template>
