<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djh7c23qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="djh7c23qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:quarkus" /></template>
