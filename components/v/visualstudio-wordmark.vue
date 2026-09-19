<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oor0rwbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oor0rwbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:visualstudio-wordmark" /></template>
