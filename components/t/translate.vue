<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqygoebky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gqygoebky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:translate" /></template>
