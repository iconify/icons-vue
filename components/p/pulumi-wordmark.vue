<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4v32jb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v4v32jb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pulumi-wordmark" /></template>
