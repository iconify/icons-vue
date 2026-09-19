<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqtu27v6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vqtu27v6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:qtest" /></template>
