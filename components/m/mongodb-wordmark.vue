<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7e5xobtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="d7e5xobtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:mongodb-wordmark" /></template>
