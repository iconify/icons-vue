<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbwlt8bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pbwlt8bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vala-wordmark" /></template>
