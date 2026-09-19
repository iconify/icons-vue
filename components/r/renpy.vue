<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pet5d9ycq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pet5d9ycq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:renpy" /></template>
