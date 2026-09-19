<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7vpkb-dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x7vpkb-dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:reactbootstrap" /></template>
