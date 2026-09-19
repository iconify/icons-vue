<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7hzi319x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="m7hzi319x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tags" /></template>
