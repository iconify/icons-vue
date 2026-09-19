<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9bibabvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="m9bibabvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:w-upper-case" /></template>
