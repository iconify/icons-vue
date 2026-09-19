<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f63gk40af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f63gk40af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:poetry" /></template>
