<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbt76bb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zbt76bb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:php" /></template>
