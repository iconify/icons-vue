<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9rcu-b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="i9rcu-b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rexx-wordmark" /></template>
