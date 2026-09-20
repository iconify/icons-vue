<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nskmalzgz.css';
import '../../css/k/khw_e2oxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nskmalzgz"/><path class="khw_e2oxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:side-nav-expand" /></template>
