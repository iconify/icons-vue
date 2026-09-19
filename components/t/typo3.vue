<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otwnocb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="otwnocb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:typo3" /></template>
