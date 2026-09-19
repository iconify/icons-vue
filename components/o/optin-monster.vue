<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-1yh6h8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y-1yh6h8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:optin-monster" /></template>
