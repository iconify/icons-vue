<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2lx5jb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v2lx5jb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trash-a" /></template>
