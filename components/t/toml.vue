<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z59glwbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z59glwbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:toml" /></template>
