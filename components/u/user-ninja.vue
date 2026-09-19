<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c400xacav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="c400xacav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-ninja" /></template>
