<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzfoecbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="wzfoecbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:zend-wordmark" /></template>
