<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvejr9afn.css';
import '../../css/g/g7jnq5bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bvejr9afn"/><path class="g7jnq5bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:semanticui" /></template>
