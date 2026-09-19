<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-peh3beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s-peh3beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:numpy" /></template>
