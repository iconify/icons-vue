<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go97lvg5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="go97lvg5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:mobx" /></template>
