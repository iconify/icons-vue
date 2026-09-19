<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac8s-6m3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ac8s-6m3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:reactrouter" /></template>
