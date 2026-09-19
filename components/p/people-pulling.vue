<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybkgz038y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ybkgz038y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:people-pulling" /></template>
