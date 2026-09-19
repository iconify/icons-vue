<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oop7cv_mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oop7cv_mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-group" /></template>
