<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei9tyne3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ei9tyne3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:pause" /></template>
