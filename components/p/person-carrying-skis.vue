<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9p0gvn4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c9p0gvn4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-carrying-skis" /></template>
