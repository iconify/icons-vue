<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq8uv6ybu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":423,"height":512};
const content = `<path class="rq8uv6ybu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nightwatch" /></template>
