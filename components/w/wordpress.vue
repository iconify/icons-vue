<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilndq7y4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="ilndq7y4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:wordpress" /></template>
