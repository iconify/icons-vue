<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/funxt_b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="funxt_b8b thealgorithms-plain-#000000"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:thealgorithms" /></template>
