<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sokatccrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sokatccrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:scalingo" /></template>
