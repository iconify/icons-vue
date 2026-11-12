<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu0u3lhjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yu0u3lhjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:unraid" /></template>
