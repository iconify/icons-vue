<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwa4pl89p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uwa4pl89p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:okta" /></template>
