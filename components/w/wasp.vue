<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe4d_o0pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xe4d_o0pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:wasp" /></template>
