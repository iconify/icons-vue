<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7itecbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="v7itecbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:x" /></template>
