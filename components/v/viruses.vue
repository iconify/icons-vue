<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en0bapbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="en0bapbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:viruses" /></template>
