<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_j8aabeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="g_j8aabeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-edit" /></template>
