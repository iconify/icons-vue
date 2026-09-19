<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww0e8n4yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ww0e8n4yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:svelte" /></template>
