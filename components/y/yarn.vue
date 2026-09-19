<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax3i4wbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ax3i4wbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:yarn" /></template>
