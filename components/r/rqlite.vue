<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-yhrxbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t-yhrxbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rqlite" /></template>
