<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5v8rch1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y5v8rch1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:purescript" /></template>
