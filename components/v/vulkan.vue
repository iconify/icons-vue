<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt_dd0byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tt_dd0byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vulkan" /></template>
