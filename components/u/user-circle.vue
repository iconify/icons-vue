<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0i-_6b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d0i-_6b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:user-circle" /></template>
