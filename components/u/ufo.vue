<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8py-sbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8py-sbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:ufo" /></template>
