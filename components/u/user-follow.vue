<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3z_u7bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g3z_u7bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:user-follow" /></template>
