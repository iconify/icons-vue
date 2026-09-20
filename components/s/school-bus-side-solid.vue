<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w47oo1b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w47oo1b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:school-bus-side-solid" /></template>
