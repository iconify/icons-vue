<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pko1oacdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pko1oacdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:modx" /></template>
