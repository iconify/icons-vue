<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mij7ueklo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mij7ueklo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vault" /></template>
