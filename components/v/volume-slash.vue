<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9enz8bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f9enz8bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:volume-slash" /></template>
