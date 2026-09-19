<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfj89pb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zfj89pb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-intersection-fill" /></template>
